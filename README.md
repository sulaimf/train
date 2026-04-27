# Train Details Dashboard

This project is now a single static HTML page for GitHub Pages.

## File

- `index.html`

## What It Does

- Fetches cancelled train details for Uppsala, Stockholm C, and Gävle
- Saves fetched records in browser `localStorage`
- Saves a submitted checkbox state per record in browser `localStorage`
- Works as a plain static page with no build step

## Notes

- The page expects a Trafikverket API key entered in the UI
- The API key is saved only in the current browser local storage
- No backend, database, or scheduler is required
