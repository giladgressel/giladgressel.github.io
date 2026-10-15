# giladgressel.github.io

Personal academic site. Plain HTML and CSS, no build step. GitHub Pages serves `index.html` directly.

## Updating

- **News:** add an `<li>` at the top of the `#news` list in `index.html`.
- **Paper:** copy an `<li>` in the matching `#publications` list (AI Security, Responsible AI, or Medical AI). Bold your name with `<b>`. Awards go in `<span class="badge award">`.
- **Featured research:** copy an `<article class="card">` in `#research`.
- **Press or talk:** add an `<li>` under `#talks`.
- Bump "Last updated" in the footer.

Preview locally with `python3 -m http.server` and open http://localhost:8000.
