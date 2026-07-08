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

## Cookie consent and analytics update

This package integrates a minimal cookie consent system for Google Analytics.

Included:
- cookie banner matching the visual language of the site
- `Reject` and `Accept` buttons
- Google Analytics loaded only after explicit `Accept`
- consent saved in `localStorage` under `traceArchiveAnalyticsConsent`
- footer link: `Cookie settings`
- Google Analytics ID: `G-D6DJ2FY8TM`
- IP anonymization enabled in the GA config

## Latest archive update

Added a new image to the archive:

- `38-arc-light.jpg` — **Arc Light** — Ritual Spaces
- Caption: A corridor shaped by shadow and patient light.

Previous latest update preserved:

- `37-small-departure.jpg` — **Small Departure** — Human Traces
- New source file: `fiat500_final_pole_removed.jpg`
- Caption: A quiet passage through a rural edge.

## Spatial archive version

This package introduces a restrained 2.5D / spatial archive layer:

- static GitHub Pages compatible
- no WebGL dependency
- SEO, filters, lightbox, cookie consent and Formspree form preserved
- image panels arranged in depth using CSS perspective
- slow scroll-based depth motion
- mobile fallback to a clean single-column archive
- `prefers-reduced-motion` respected
- footer control: `Reduce motion` / `Enable motion`
- spatial preference saved in `localStorage` under `traceArchiveSpatialReduced`
