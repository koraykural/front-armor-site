# front-armor-site

Public site for the Front Armor app: support and privacy policy pages, served by GitHub Pages at https://koraykural.github.io/front-armor-site/. Plain static HTML, no build step.

`game/` is the Unity WebGL build of Front Armor (from the front-armor repo: `unity/Builds/web`, without `StreamingAssets/`). Pushing changes under `game/` deploys it to https://front-armor.koraykural.com via `.github/workflows/deploy.yml` (restricted deploy key, see koraykural-infra).
