# IRONLOG — iPhone workout tracker

A minimalist black-and-white workout tracker with:
- A customizable Sunday–Saturday weekly schedule
- Custom exercise names, set counts, target reps, and starting weights
- Per-set weight/reps logging and completion checkmarks
- Workout history, total volume, and best logged weights
- Local saving plus JSON export/import backups
- Installable PWA manifest and offline cache

## Get it onto your iPhone Home Screen

The files need to be hosted at an HTTPS URL for the installable web-app features to work. The easiest free option is GitHub Pages:

1. Sign in or create an account at https://github.com
2. Create a new public repository, e.g. `ironlog`
3. Upload `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, and `icon-512.png` from this folder.
4. In the repository, open **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish your site. Open the Pages URL on your iPhone in **Safari**.
6. Tap **Share → Add to Home Screen**. If offered, enable **Open as Web App**, then tap Add.

You can also host the files on another HTTPS static host. Opening `index.html` directly as a file is fine for a quick preview, but it won't provide full PWA install/offline behavior.

## Important data note
Workout data is stored locally in the browser on that device. It does not automatically sync between devices. Use **Progress → Export Backup** periodically, especially before clearing browser data or switching phones.
