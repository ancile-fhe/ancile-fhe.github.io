# Ancile website

The product page for Ancile, served by GitHub Pages at https://ancile-fhe.github.io.

This branch has only the website. The Ancile code is on the `main` and `dev` branches.

- `index.html`: the full site, one static file with no build step. It loads only Google Fonts.
- `.nojekyll`: tells GitHub Pages to serve the files as they are.

To preview it locally, open `index.html` in a browser, or run `python3 -m http.server` in this folder.

All numbers on the page come from real Ancile runs on the example task `mlp_square`. When the results change, update the `T` and `RUNS` data in the script at the end of `index.html`.
