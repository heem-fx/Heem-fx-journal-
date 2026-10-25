HEEM FX Trading Journal — installable web app package

FILES
- index.html: the journal app
- manifest.webmanifest: app name and install settings
- sw.js: offline cache/service worker
- icon-192.png and icon-512.png: home-screen icons

IMPORTANT
This is a Progressive Web App (PWA), not a signed APK. For the Android install prompt and offline service worker to work, publish these files to an HTTPS website. You can do this free with GitHub Pages or Netlify. Opening index.html directly from Downloads may let you test the journal, but will not install the PWA properly.

PHONE-ONLY DEPLOYMENT OPTION (GitHub Pages)
1. In Chrome on Android, create/sign in to a GitHub account at github.com.
2. Create a new public repository, e.g. heem-fx-journal.
3. Upload all five app files and this README into the repository root (use Add file / Upload files; select the files from Downloads).
4. In the repository, open Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
6. Wait for GitHub Pages to publish. Open the Pages URL shown there in Chrome.
7. In Chrome, tap ⋮ → Install app or Add to Home screen. Wording varies by Chrome version.
8. Launch HEEM FX from the new home-screen icon. Test offline by opening it once while online, then briefly turning off data/Wi-Fi.

DATA AND SAFETY
Trade records are saved in browser local storage on that device. They do not sync between devices. Export CSV backups regularly from Settings & Backup. Clearing browser/site data can erase records. This app does not connect to MT5, place trades, or fetch live market prices.
