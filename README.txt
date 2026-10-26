GYM JAO — COMPLETE PWA PACKAGE

Folder layout:
- index.html
- manifest.json
- sw.js
- icons/icon-192.png
- icons/icon-512.png
- icons/icon-maskable-512.png
- icons/apple-touch-icon.png

WHAT WAS CHANGED:
- Added PWA manifest link, app icon metadata, and service-worker registration.
- Added a correctly structured manifest with relative paths for the /Gym-jao/ GitHub Pages project.
- Added a service worker that caches the app shell and supports offline opening after the first successful load.
- Kept the existing workout tracker HTML and app logic as the basis; no workout features were intentionally rewritten.

HOW TO UPLOAD:
1. Unzip this package.
2. Open your GitHub repository for Gym-jao.
3. Upload/replace index.html and sw.js and manifest.json at the repository root.
4. Create an icons folder and put all four icon PNGs inside it.
5. Commit changes and wait for GitHub Pages to redeploy.
6. Open https://sshreyansh-meow.github.io/Gym-jao/ in Chrome, refresh, then check Chrome menu for Install app.
7. If Chrome still shows old installation state, Chrome > Settings > Site settings > All sites > select the site > Clear & reset; then reload the site.

IMPORTANT:
- Make a backup from the existing tracker before switching. Browser/localStorage data does not automatically transfer between the old page and the installed PWA.
- Restore your backup in the new version after opening it.
- The app uses Chart.js from a CDN, so charts may need internet.
- The ZIP is a ready-to-upload package; it does not itself deploy the website.
