# Raven Olisaro — The Trace Archive

Static GitHub Pages package for Raven Olisaro / The Trace Archive.

## Update included in this package

This version adds a dedicated **Prints** section for sporadic, manual print requests.

Implemented:

- navigation item: `Prints`
- new page section: `Fine art prints available on request`
- no e-commerce checkout
- no cart
- no “Buy now” button
- manual request form through Formspree
- note clarifying that this is not an automated e-commerce service
- suggested print selection using images already present in `/assets`
- Google Analytics remains gated behind explicit cookie consent
- cookie settings link remains in the footer

## Important deployment note

This package expects the existing `/assets` folder already present in the GitHub repository to remain in place.

Do not delete the existing `/assets` folder when uploading this update.

Recommended upload method:

1. Open the repository on GitHub.
2. Upload/replace these files at repository root:
   - `index.html`
   - `README.md`
   - `manifest.json`
   - `robots.txt`
   - `sitemap.xml`
   - `favicon.svg`
   - `googlebd07545311086ccb.html`
3. Keep the existing `/assets` folder unchanged.
4. Commit the update.
5. Wait for GitHub Pages to redeploy.

## Form endpoint

Forms submit to:

`https://formspree.io/f/xkoeezdv`

Forms included:

- archive response form: “Leave a trace”
- print request form: “Request a print”

## Analytics

Google Analytics ID:

`G-D6DJ2FY8TM`

Analytics is loaded only after explicit `Accept` in the cookie banner. Consent is saved in `localStorage` under:

`traceArchiveAnalyticsConsent`
