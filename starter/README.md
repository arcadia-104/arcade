# Starter voor een eigen arcade

Alles wat een nieuwe maker nodig heeft voor een eigen arcade op GitHub Pages
(`arcadia-104/<naam>-arcade`). Gebruikt in les 3.1 van Informatica.

- `index.html`: de startpagina met het lijstje games. Vervang `jouwnaam` door de GitHub-naam.
- `_start/`: een kale startgame (pijltjes, munten, score) om nieuwe games van te kopiëren.
- `fonts/`: Press Start 2P (SIL Open Font License, zie `fonts/OFL.txt`).

Zo zet je hem in een nieuwe arcade (na `gh auth login`, vanuit de map van de nieuwe arcade):

```sh
gh repo clone arcadia-104/arcade /tmp/arcade -- --depth 1
cp -r /tmp/arcade/starter/. .
sed -i 's/jouwnaam/<naam>/g' index.html
rm README.md
```
