# Arcade

Games die we zelf maken, gewoon in je browser. Niets installeren: klik en speel.

**Speel ze hier: <https://arcadia-104.github.io/arcade/>**

Elke maker heeft een eigen arcade, met al zijn eigen games. Deze pagina verzamelt ze allemaal.

## Zelf een arcade beginnen

Je eigen arcade is een repo `arcadia-104/jouwnaam-arcade` met een startpagina en een map per
game. Alles wat je nodig hebt om te beginnen staat in [`starter/`](starter): een startpagina en
een kale startgame om mee te oefenen.

```sh
gh repo create arcadia-104/jouwnaam-arcade --public --clone
cd jouwnaam-arcade
gh repo clone arcadia-104/arcade /tmp/arcade -- --depth 1
cp -r /tmp/arcade/starter/. .
sed -i 's/jouwnaam/<jouw GitHub-naam>/g' index.html
rm README.md
git add . && git commit -m "Mijn arcade: eerste versie" && git push
```

Zet daarna GitHub Pages aan: **Settings → Pages → Deploy from a branch → main → / (root)**.
Na een minuut staat je arcade op `https://arcadia-104.github.io/jouwnaam-arcade/`.

## Je arcade op deze pagina

Wil je dat je arcade hier ook tussen staat? Lees [CONTRIBUTING.md](CONTRIBUTING.md).

## Licentie

Code: [MIT](LICENSE). Het lettertype Press Start 2P valt onder de SIL Open Font License
(zie `starter/fonts/OFL.txt`).
