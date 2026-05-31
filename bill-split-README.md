# The Couples Bill-Split Calculator

A small, installable web app (PWA) that splits a couple's shared bills by how much each
partner earns — by hourly wage or salary — using a proportional or 50/50 split. Works
offline once installed, and adds to your phone's home screen like a native app.

## Files
- `index.html` — the app
- `manifest.webmanifest` — makes it installable
- `sw.js` — service worker (offline support + installability)
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `favicon-32.png` — icons

All paths are **relative**, so it works in a GitHub Pages project site (e.g.
`https://yourname.github.io/bill-split/`).

## Put it on GitHub Pages (free hosting + HTTPS)
1. Create a new repository on GitHub (e.g. `bill-split`).
2. Upload **all** the files in this folder to the repository root
   (drag-and-drop them into GitHub's "Add file → Upload files", then Commit).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source: Deploy from a branch**,
   **Branch: `main`**, **Folder: `/ (root)`**, then **Save**.
5. Wait ~1 minute. Your app will be live at
   `https://YOURNAME.github.io/bill-split/`.
   (HTTPS is provided automatically — that's required for "Add to Home Screen".)

## Add it to your home screen
Open the live URL on your phone:
- **iPhone/iPad (Safari):** tap the **Share** icon → **Add to Home Screen**.
- **Android (Chrome):** tap the **Install app** button in the header, or the
  browser menu → **Install app / Add to Home screen**.

That's it — it will open full-screen with its own icon, and keep working offline.

## Notes
- The app uses **gross** income (before taxes). Real take-home pay is lower, so treat
  results as a starting point, not financial advice.
- All data stays in the browser; nothing is uploaded or saved to any server.
