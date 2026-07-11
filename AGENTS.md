# AGENTS.md

## Cursor Cloud specific instructions

This repository is a single-page **static website** ("AquaFelix" water purification showcase). It consists of `index.html` (all CSS is inline) plus the hero image `AquaFelix water purification showcase.png` and a Google site-verification file. There is no build system, package manager, dependency manifest, lint config, or test suite.

- **Run (dev):** Serve the folder with any static file server, e.g. `python3 -m http.server 8000` from the repo root, then open `http://localhost:8000/`.
- **Build:** None. The site is deployed as-is (served statically / via GitHub Pages).
- **Lint / Test:** None configured.
- **Gotcha:** The hero image filename contains spaces (`AquaFelix water purification showcase.png`). It works when referenced from `index.html`, but a direct HTTP request must URL-encode the spaces (`%20`).
