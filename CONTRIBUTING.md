# Meedoen

Fijn dat je wilt helpen! Dit project werkt zoals de meeste open source projecten. Wat je hier
leert, werkt dus overal.

## Zo werkt het

1. **Begin met een issue.** Een bug gevonden of een idee? Maak eerst een [issue](../../issues)
   en beschrijf wat je zag of wilt.
2. **Maak een fork en een branch.** Een fork is je eigen kopie van het project, een branch is
   een zijspoor waarop je werkt zonder het origineel te veranderen.
   ```sh
   gh repo fork arcadia-104/arcade --clone
   cd arcade
   git switch -c mijn-arcade-erbij
   ```
3. **Maak je verandering.** Klein houden: één idee per branch.
4. **Test het.** Open `index.html` in je browser (`xdg-open index.html`) en kijk of alles werkt.
5. **Commit** met een duidelijke boodschap: wat heb je gedaan en waarom?
   ```sh
   git add .
   git commit -m "Voeg de arcade van jouwnaam toe"
   ```
6. **Push en maak een pull request:**
   ```sh
   git push -u origin mijn-arcade-erbij
   gh pr create
   ```
7. **Review.** De eigenaar bekijkt je verandering en stelt misschien vragen of vraagt om
   aanpassingen. Dat is normaal en geen oordeel over jou: iedereens code wordt gereviewd.
   Push nieuwe commits naar dezelfde branch, dan wordt je pull request vanzelf bijgewerkt.
8. **Merge.** Is alles goed? Dan wordt je verandering samengevoegd met `main`.

Niemand zet iets direct op `main`, ook de eigenaars niet. Alles gaat via een pull request.

## Je arcade toevoegen

Open `index.html` en zet je arcade in het lijstje, net als de andere:

```html
<li><a href="https://arcadia-104.github.io/jouwnaam-arcade/">De arcade van jouwnaam</a></li>
```

## Huisregels

- Games zijn **geschikt voor iedereen**.
- **Geen echte namen, scholen, adressen of foto's**, niet in games, commits of issues. Gebruik je
  GitHub-naam.
- Kopieer geen plaatjes, muziek of namen van bestaande games. Maak je eigen.
