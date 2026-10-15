# giladgressel.github.io

Personal academic site. Plain HTML and CSS, no build step. GitHub Pages serves `index.html` directly.

## Updating

- **News:** add an `<li>` at the top of the `#news` list in `index.html`.
- **Paper:** copy an `<li>` in the matching `.pubs` list under `#publications` (AI Security, Responsible AI, or Medical AI). Each row is a year (`<time>`), the paper, and a venue. Use `<a class="t" href="…">` for the title when there is a link, `<span class="t">` otherwise. Bold your name with `<b>`. Add `top` to the venue (`class="venue top"`) for top-tier venues, and put awards in `<span class="award">` inside the venue.
- **Featured research:** copy an `<article class="feature">` in `#research`. Figures live in `assets/research/`.
- **Press or talk:** add an `<li>` under `#talks`.
- Bump "Last updated" in the footer. After changing `style.css`, bump its `?v=` number in `index.html` so browsers fetch the new file.

Preview locally with `python3 -m http.server` and open http://localhost:8000.
