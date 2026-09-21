# special-bouquet-tracker

A simple single-page web app for tracking completed special bouquets and calculating the flowers still needed for incomplete ones.

## GitHub Pages

This repository is ready to publish as a static site from the `main` branch root.

The app entry point is `index.html`.

## How to use

1. Open `index.html` directly in a browser, or serve the repo with any static file server.
2. Use the search box to find a bouquet.
3. Toggle each bouquet between completed and incomplete.
4. The right-hand panel updates automatically with the aggregate flower requirements for all incomplete bouquets.
5. Completion state is stored in the browser via `localStorage`.

## Notes

- The app includes the bouquet dataset inferred from the provided reference tables.
- Bouquets marked as completed in the source images are pre-marked as completed, including `虎斑搖籃` and `奶貓搖鈴`.
