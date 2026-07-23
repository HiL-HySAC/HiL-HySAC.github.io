# HiL-HySAC project page

This repository contains the static project page published at
<https://evanzhangyifang.github.io/HiL-HySac.github.io/>.

The site intentionally has no build step or framework. It is plain HTML, CSS,
and JavaScript, so GitHub Pages can serve it directly and contributors can
preview it with any local web server.

## Preview locally

From the repository root:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Add the final project content

The page currently contains clearly labelled placeholders because the paper
metadata, abstract, results, authors, and public resource links have not yet
been provided. Follow [docs/CONTENT.md](docs/CONTENT.md) for the exact fields
that need to be supplied.

Most text is in `index.html`. Visual styling is in `styles.css`, and the small
copy-to-clipboard interaction is in `script.js`.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this GitHub repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder.
4. Save and wait for the Pages deployment to finish.

The expected URL is
<https://evanzhangyifang.github.io/HiL-HySac.github.io/>.

## Repository layout

```text
.
├── assets/
│   └── favicon.svg
├── docs/
│   └── CONTENT.md
├── .nojekyll
├── index.html
├── script.js
└── styles.css
```

## Before release

- Replace every `TODO` comment in `index.html`.
- Search for placeholder em dashes (`—`) and “coming soon”.
- Test the page at desktop and mobile widths.
- Confirm every external link and the citation.
- Add a social preview image at `assets/social-card.png`, then add
  `<meta property="og:image" content="https://evanzhangyifang.github.io/HiL-HySac.github.io/assets/social-card.png">`
  to the page `<head>`.
- Add the project’s chosen license. No license is assumed by this scaffold.

## License

No license has been selected yet. Add a `LICENSE` file before accepting external
contributions or reusing the site outside this repository.
