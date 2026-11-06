# Utah Permit Prep (PWA)

A plain HTML app. No build step, no accounts, no database. Just files.

## Put it online with GitHub Pages
1. On GitHub, create a new **public** repository, e.g. `utah-permit-prep`.
2. Upload everything in this folder (including the `icons` folder, `.nojekyll`, `sw.js`, and `manifest.webmanifest`) to the repository root.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then Save.
4. After a minute or two, the app is live at `https://YOUR-USERNAME.github.io/utah-permit-prep/`.

## Install it on an iPhone
Open the link in **Safari**, tap Share, then **Add to Home Screen**. It opens full screen and works offline after the first load.

## Updating it later
Edit `index.html` (or upload a new copy) and commit. The app picks up changes the next time it is opened with a connection.
If an update ever seems stuck, change `permit-prep-v1` to `permit-prep-v2` in `sw.js`.
