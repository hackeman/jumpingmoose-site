# jumpingmoose.se

The website of Jumping Moose AB, served by GitHub Pages straight from the root of the
`main` branch (Settings → Pages → Deploy from a branch → `main` / root).

- `index.html` is the whole site; `assets/` holds the logo, favicons and link-preview image.
- `CNAME` points the site at jumpingmoose.se.
- `.nojekyll` makes Pages serve the files as they are.

The brand kit the assets come from is kept in a separate, private repo. If the brand files
change, copy the new versions into `assets/` with the same file names.

Preview locally: `python3 -m http.server 8000`, then open http://localhost:8000.
