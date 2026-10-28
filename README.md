# Craftily Created Creations

Public repo for the privacy policies of my apps (brand: **Craftily Created Creations**), published as a small static GitHub Pages site. No build step is needed (`.nojekyll` is included).

## Layout

- `index.html` – home page listing the apps, with contact details.
- `<app-slug>/privacy.html` – one folder per app holding its privacy policy, e.g. `e-fishcient/privacy.html`.
- `.nojekyll` – tells GitHub Pages to serve the files as-is.

All pages are plain HTML with inline CSS; no external resources are loaded.

## Adding a new app

1. Create a folder named after the app in lowercase with hyphens, e.g. `my-new-app/`.
2. Copy `e-fishcient/privacy.html` to `my-new-app/privacy.html` and edit the text (app name, package, data, permissions, "Last updated" date, contact).
3. Add a list item for the app in `index.html` linking to `my-new-app/privacy.html`.
4. Open a pull request and merge it; Pages redeploys automatically.

## URLs

Pattern: `https://dennehy95.github.io/Craftily-Created-Creations/<app-slug>/privacy.html`

E-Fishcient (use this in Google Play Console):
https://dennehy95.github.io/Craftily-Created-Creations/e-fishcient/privacy.html

## Enabling GitHub Pages

Pages must be enabled once: **Settings > Pages > Build and deployment > Deploy from a branch > `main` > `/ (root)` > Save**.

## Contact

bryandennehy1995@gmail.com
