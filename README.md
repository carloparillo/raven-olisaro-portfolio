# Raven Olisaro — The Trace Archive

Static GitHub Pages package for **The Trace Archive**, designed as a coherent photographic project rather than a generic portfolio.

## Main refinements in this package

- stronger curatorial positioning in the hero and archive introduction
- dedicated **Project Grammar** section to make the photographic direction explicit
- more editorial archive sequencing
- filter descriptions for each category
- more precise **About the Archive** section
- integrated **Leave a trace** form using Formspree
- cleaned metadata, valid web manifest and updated sitemap
- fixed and simplified lightbox / filter / form JavaScript

## Included sections

- Hero
- Project Grammar
- Archive
- Grammar / Direction
- About the Archive
- Leave a trace

## Deployment

1. Upload all files to the root of the GitHub repository used for GitHub Pages.
2. Make sure GitHub Pages is pointing to the correct branch/root.
3. If the repository URL changes, update these values in `index.html`, `manifest.json`, `robots.txt` and `sitemap.xml`:
   - canonical URL
   - Open Graph URL/image paths
   - sitemap URL
   - start_url / scope

## Form endpoint

The contact form is configured to submit to:

`https://formspree.io/f/xkoeezdv`

If you change the form endpoint in the future, update the `action` attribute of the form in `index.html`.
