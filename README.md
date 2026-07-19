# Cheese Mecca

A GitHub Pages-friendly catalog, digital booklet, and slideshow for 104 cheeses.

## Drop into GitHub
1. Create a new repository.
2. Upload everything inside this folder to the repository root.
3. In **Settings → Pages**, deploy from the `main` branch root.
4. Open `/cheese/` for the catalog. The root automatically redirects there.

## Structure
- `/cheese/` — catalog, booklet, slideshow, and cheese detail profiles
- `/game/` — reserved location for the future cheese-combination game
- `/assets/data/cheeses.json` — the single catalog database
- `/assets/css/cheese-mecca.css` — all visual styling
- `/assets/js/cheese-mecca.js` — filtering, booklet, slideshow, and detail logic
- `/cheeses/<slug>/` — 104 lightweight entry links, ready for future individual QR codes

## Individual cheese links
Every cheese also has a stable folder URL, for example:

`/cheeses/halloumi/`

That page forwards to:

`/cheese/?cheese=halloumi`

This lets future QR codes point at permanent, readable URLs without duplicating the full catalog code 104 times.

## Editing
Edit cheese details in `/assets/data/cheeses.json`. Fields marked as inferred can be adjusted without touching the interface.
