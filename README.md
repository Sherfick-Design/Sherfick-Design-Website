# Sherfick Design Website — Concept 1 / Responsive Build

A mobile-ready single-page website for Sherfick Design.

## Files

- `index.html` — site content and structure
- `styles.css` — responsive desktop/tablet/mobile styling
- `script.js` — mobile navigation, reveal animation, copyright year
- `assets/sherfick-design-logo.png` — full Sherfick Design logo
- `assets/sherfick-design-mark.png` — SD logo mark

## Preview locally

Open `index.html` in a browser, or run a small local web server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Cloudflare Pages

For a static HTML site:

- Framework preset: **None**
- Build command: leave blank
- Build output directory: `/`
- Production branch: `main`

## Before final launch

The current contact form uses a `mailto:` action. Replace it with a proper form endpoint (such as a Cloudflare Worker or form service) before relying on it for client leads.
