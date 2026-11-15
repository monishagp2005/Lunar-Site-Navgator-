# Selene — Lunar Site Planner

An interactive concept dashboard for comparing lighting and direct-to-Earth visibility at candidate lunar south-pole landing sites.

## Deploy with GitHub Pages

This package includes a GitHub Actions workflow at `.github/workflows/pages.yml`.

1. Upload the contents of this folder to the root of a GitHub repository on the `main` branch.
2. Open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. Push to `main`, or run **Deploy to GitHub Pages** from the repository's Actions tab.
4. Open the published URL shown in the workflow run summary.

The site is static HTML served from `index.html`; it needs no build step or package installation.

## Interactions

- Choose Shackleton Rim, Connecting Ridge, or Malapert Massif.
- Change the landing date and mission phase.
- Scrub or play through the local lunar day.
- Compare illustrative sunlight and Earth visibility profiles.
- View the Sun and Earth together against the local horizon.

## Data note

This is a visual concept model. Coordinates, terrain masks, lighting, and communication estimates are illustrative and are not suitable for operational mission planning. Replace them with validated terrain and ephemeris products before mission decisions.
