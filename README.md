# Taskflow

Offline-ready task manager PWA (black, blue-green, violet liquid-glass UI).

## Deploy with GitHub Pages
1. Create a GitHub repository and upload ALL files from this folder (including the `icons` folder and `.nojekyll`).
2. Settings > Pages > Deploy from a branch > `main` and `/ (root)` > Save.
3. Wait 1-2 minutes, then open `https://<username>.github.io/<repo>/` (it must be this https link, not a file on your phone).
4. Android Chrome: tap **Install app** in the app, or menu (⋮) > Install app. iPhone: Safari > Share > Add to Home Screen.

## Your data
- Saved on-device (localStorage + IndexedDB) and works fully offline.
- Uninstalling an app makes the browser/phone delete its stored data. To keep your tasks, tap **Save backup** (save the file to Google Drive, Files, or email it to yourself). After reinstalling, tap **Restore** and pick that file.

## Updating
Change `taskflow-v2` to `taskflow-v3` in `sw.js` whenever you change the app.
