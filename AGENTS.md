# AquaFelix Website

A single-page static marketing website for the AquaFelix water purification business. There is no backend, database, build system, or package manager.

## Cursor Cloud specific instructions

- This is a **purely static site**. The entire product is `index.html` (all CSS inlined). Assets: `AquaFelix water purification showcase.png` (hero image) and `google190cc1a9ec9e7185.html` (Google Search Console verification).
- **There is no build, lint, or test tooling** — no `package.json`, `Makefile`, or dependencies to install. The update script is effectively a no-op.
- **Run/serve locally** from the repo root: `python3 -m http.server 8000`, then open `http://localhost:8000/index.html`. Serving over HTTP (rather than `file://`) is recommended so relative asset paths resolve.
- **Font Awesome icons** load from a CDN (`cdnjs.cloudflare.com`). Without internet access the page layout/content still renders fine, but the icon glyphs will not display.
