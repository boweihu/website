# boweihu.com

Personal website of Bo-Wei Hu — a minimal, hand-written static site (plain HTML/CSS, no framework).

## Structure

- `site/` — the published site, served exactly as-is:
  - `index.html` (Home), `about.html`, `research.html`
  - `styles.css` — shared styles
  - `images/`, `uploads/resume.pdf`, `favicon.svg`
- `netlify.toml` — Netlify config; publishes `site/` with no build step.

## Deploy

Hosted on Netlify, connected to this repo. Push to `main` and Netlify
auto-deploys `site/` to boweihu.com.

## Local preview

Serve the `site/` folder with any static server, for example:

```bash
cd site && python3 -m http.server 8000
# then open http://localhost:8000
```
