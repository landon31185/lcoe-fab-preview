# LCOE FAB Sunburst Preview

This repo hosts a simple preview for Lottie animations used behind the LCOE FAB.

## Preview

Open the GitHub Pages URL after the first push completes. Use the dropdown to switch between JSON animations.

## Local development

- Serve locally to avoid CORS:
  - `python3 -m http.server 5500`
  - Open `http://localhost:5500/index.html`

## Files

- `index.html`: FAB preview + Lottie player with dropdown
- `lcoe-fab-sunburst.json`: Base animation
- `lcoe-fab-sunburst-v1.json`, `lcoe-fab-sunburst-v2.json`: Variations (edit as needed)
