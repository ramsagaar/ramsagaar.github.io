# Portfolio site — Venkata Ram Sagar Konagandla

Single-file academic portfolio (`index.html`, no build step) with images and the public CV in `assets/`. Designed for free hosting on GitHub Pages at **https://ramsagaar.github.io**.

The editable CV source lives in `../cv-build/cv.html` (with phone). The no-phone variant and both PDFs are regenerated from it via headless Edge; the no-phone PDF is copied into `assets/` for the site's download button.

## Status

Everything is wired in: headshot, Halliburton photo, thesis figures (from the URS presentation), publications with DOIs, profile links (Scholar / ORCID / LinkedIn / GitHub), and the no-phone CV download.

## Deploy on GitHub Pages

1. Sign in as `ramsagaar` on GitHub and create a new **public** repository named exactly `ramsagaar.github.io`.
2. Put `index.html` and the `assets/` folder at the repository root and push.
3. The site is live at `https://ramsagaar.github.io` within a couple of minutes (Settings → Pages to confirm).
