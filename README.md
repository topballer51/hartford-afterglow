# Hartford Afterglow

Recovered browser v0.2 prototype, preserved from ChatGPT Library.

## Play

Published game: https://topballer51.github.io/hartford-afterglow/

Use W/A/S/D to move. Drag the left on-screen stick to move and the right stick to look. This is an early prototype: the gold beacon mission and USE button do not yet implement completion or interaction.

## Local workflow

Open this repository folder in VS Code and add the same folder as a local project in Codex. Ask Codex to edit and test the existing game, then review changes in GitHub Desktop, commit, and push to origin.

Serve the repository with a local HTTP server and open http://127.0.0.1:8000 in Safari. With Python installed:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Refresh Safari after saving changes. Keep the server running while testing; stop it with Control-C.

## Deployment

GitHub Pages uses Deploy from a branch, main, /(root). Pushing to main publishes updates automatically. The .nojekyll marker serves the static game directly. The game is self-contained in index.html and requires no package installation or build step.

The original download remains in ChatGPT Library as hartford_afterglow_browser_v02.html. Repository history preserves the recovered version.
