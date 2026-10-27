# Hookline & Sinker Games — site

Support and privacy pages for the studio's games, published with GitHub Pages
(plain static HTML, no build step). App Store Connect links to these as each
game's Support URL and Privacy Policy URL.

| Page | Path |
|---|---|
| Studio home | `/` |
| Nooked support / privacy | `/nooked/`, `/nooked/privacy.html` |
| Bubble Gust support / privacy | `/bubble-gust/`, `/bubble-gust/privacy.html` |

Every page uses `site.css`. Game icons and the studio logo live in `assets/`.
`.nojekyll` stops GitHub Pages from running Jekyll over the files.

To add a game: copy one game's folder, edit the text, and add it to the list in
`index.html`. Update a privacy page's "Last updated" date whenever its text changes.
