# Taskflow

Offline-ready task manager PWA. Black, blue-green and violet liquid-glass UI. Tasks are saved on your device.

## Deploy with GitHub Pages
1. Create a new repository on GitHub and upload all files from this folder (keep the `icons` folder).
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your app is live at `https://<your-username>.github.io/<repo-name>/`.
5. Open that link on your phone and use **Add to Home Screen** (or the in-app **Install app** button on Chrome/Edge).

## Files
- `index.html` - the whole app (HTML, CSS, JS)
- `manifest.webmanifest` - install details
- `sw.js` - offline cache (change `CACHE` version when you update the app)
- `icons/` - app icons
