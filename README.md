# Activity Timer (personal PWA)

Files: index.html (the app), manifest.webmanifest + icon-192.png + icon-512.png (installable app), sw.js (offline support).

## 1. Put it on GitHub Pages (free)
1. Sign in at github.com, click **New repository**. Name it e.g. `activity-timer`. Public is fine: your session data is never stored in the repo, only in your own browser.
2. Unzip this folder. In the repo click **Add file > Upload files**, drag in ALL files (index.html, sw.js, manifest.webmanifest, both icons), then **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment" choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. After a minute or two your app is live at `https://YOUR-USERNAME.github.io/activity-timer/`.

## 2. Install it
- **Laptop (Chrome/Edge):** open the link, click the install icon at the right end of the address bar, then Install. It opens in its own window.
- **Android (Chrome):** menu > Install app / Add to Home screen.
- **iPhone (Safari):** Share > Add to Home Screen.

## 3. Move your existing data (do this once, on the laptop)
1. Open the old preview page, go to **Backup & restore**, click **Show backup**, then **Copy**.
2. Open the new hosted app, paste into the backup box, click **Import & merge**.
Each browser/device keeps its own data. Phone and laptop will NOT match until the Phase 4 sync is added. Use **Download file** now and then as a backup.

## 4. Updating the app later
Replace index.html in the repo (Add file > Upload files, same name). When you are online the installed app picks up the new version on its next open or refresh.
