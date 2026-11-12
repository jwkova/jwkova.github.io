# Personal site

Plain static HTML + CSS, served by GitHub Pages. No build step.

- `index.html` — the whole page (blurb, papers)
- `style.css` — navy/white theme; dark mode follows the visitor's OS setting
- `.nojekyll` — tells GitHub Pages to serve the files as-is

Preview locally: `python3 -m http.server 8000` in this directory, then open http://localhost:8000.

To add a paper, copy one `<li class="pub">…</li>` block in `index.html`.
