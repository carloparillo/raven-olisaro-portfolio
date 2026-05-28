# Raven Olisaro — GitHub Pages Portfolio

Static photography portfolio designed for GitHub Pages.

## Files

- `index.html`: complete one-page website with embedded CSS and JavaScript
- no build tools required
- no dependencies
- works directly on GitHub Pages

## How to publish on GitHub Pages

1. Create a new public repository on GitHub.
2. Name it either:
   - `ravenolisaro.github.io` for a user site, or
   - any name you prefer, e.g. `raven-olisaro-portfolio`.
3. Upload `index.html` to the repository root.
4. Go to `Settings` → `Pages`.
5. Under `Build and deployment`, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. GitHub will generate the public site URL.

## Important

This first version uses image URLs from the current Wix CDN. For a proper migration, replace those URLs with local files:

- create an `assets/images/` folder
- upload optimized JPG/WebP files
- update the `src` fields in `index.html`

Recommended image export:
- long edge: 1800–2400 px
- quality: 80–90
- format: JPG or WebP
- keep file size preferably below 700 KB per image
