# OSUIT ETDE ABET Unified Hub

This is one responsive ABET system for desktop, tablet, and phone.

## GitHub Pages setup

1. Create one new public GitHub repository.
2. Upload all files and folders from this package to the repository root:
   - `index.html`
   - `manifest.webmanifest`
   - `service-worker.js`
   - `icons/`
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save and wait for the GitHub Pages address.

## How the layout changes

- Desktop: full side navigation and management tools.
- Tablet: touch-friendly responsive layout with full access.
- Phone: bottom navigation, slide-out menu, quick lookup, and global search.

All features are part of the same `index.html` file.

## Install as an app

- Android: open the GitHub Pages site in Chrome and choose **Install app**.
- iPhone/iPad: open in Safari and choose **Share → Add to Home Screen**.
- Windows/macOS: use the browser install icon when available.

## Data storage

This edition stores data in the local browser. The same GitHub website can be opened on every device,
but browser data does not automatically synchronize between devices.

Use the built-in Faculty Submission/export and master consolidation tools to transfer data.

For live shared data across devices and instructors, connect this unified interface to Firebase in a future cloud-sync edition.


## GitHub Desktop

See `GITHUB_DESKTOP_SETUP.md` for step-by-step desktop publishing and update instructions.
