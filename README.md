# HiL-HySAC: real-world RL with hybrid action spaces

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

## Project

This page presents a real-world online reinforcement learning framework for
robot manipulation with hybrid action spaces. The method uses centralized
training with decentralized execution (CTDE): separate actor-agents control the
continuous Cartesian arm pose and discrete gripper actions, while a centralized
multi-head critic coordinates training through reward decomposition.

The project metadata and reported results are recorded in
[docs/PROJECT.md](docs/PROJECT.md).

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
│   └── PROJECT.md
├── .nojekyll
├── index.html
├── script.js
└── styles.css
```

## Before release

- Add the official paper URL and BibTeX once available.
- Replace the CSS-rendered result summary with the final publication figure.
- Test the page at desktop and mobile widths.
- Confirm every external link and the citation.
- Add a social preview image at `assets/social-card.png`, then add
  `<meta property="og:image" content="https://evanzhangyifang.github.io/HiL-HySac.github.io/assets/social-card.png">`
  to the page `<head>`.
- Add the project’s chosen license. No license is assumed by this scaffold.

## License

No license has been selected yet. Add a `LICENSE` file before accepting external
contributions or reusing the site outside this repository.
