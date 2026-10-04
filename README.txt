Daily CORE Development — iOS Safari / Home-Screen Web App

IMPORTANT
This package is intended to be hosted on an HTTPS website. Do not open index.html from the iPhone Files app as a local document.

HOSTING
Upload all files in this folder together to the same HTTPS web directory:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-180.png
- icon-512.png

IPHONE / IPAD STARTUP
1. Open Safari.
2. Enter the HTTPS web address where this folder is hosted.
3. Confirm the Daily CORE Development tracker loads.
4. Tap Safari Share.
5. Choose Add to Home Screen.
6. Open Daily CORE from its Home Screen icon thereafter.

OFFLINE
After the hosted app has loaded successfully, the service worker caches the app files for offline use. Exercise records, difficulty entries, body-weight entries and archive history remain in browser-local storage on that device/browser.

ARCHIVES
Continue using Print / Save PDF before a biweekly rollover to retain an independent historical file outside browser storage.
