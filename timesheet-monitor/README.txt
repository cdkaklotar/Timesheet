TIMESHEET MONITOR - LOCAL PACKAGE

Files:
- index.html
- app.js
- manifest.json
- service-worker.js

QUICK LAPTOP USE
1. Unzip this package.
2. For simple browser use, open index.html.
3. Your entries are saved in that browser's local storage.
4. Use "Save backup" to create timesheet-data.json.
5. Use "Load JSON" to restore or transfer your data.

OFFLINE/PWA INSTALLATION
A service worker/PWA normally needs to be served from localhost or HTTPS, not opened only as file://.
If Python is installed on a laptop, open a terminal in this folder and run:
    python -m http.server 8080
Then browse to localhost:8080.

MOBILE
Copy the package to a device or serve it from a local/HTTPS web server. The responsive interface works on mobile browsers. JSON import/export is the portable cross-device backup method.

IMPORTANT
Keep timesheet-data.json backups. Clearing browser/site data can remove locally stored entries.
