TIMESHEET MONITOR PWA

This is the installable PWA package.

IMPORTANT: Do not open index.html directly with file:// for PWA installation. Service workers and normal PWA installation require the application to be served from localhost during laptop testing or from an HTTPS site for phone installation.

LOCAL LAPTOP TEST
1. Unzip the package.
2. Open a terminal in timesheet-monitor-pwa.
3. If Python is available, run: python -m http.server 8080
4. Open http://localhost:8080 in Chrome or Edge.
5. Use the browser's install option.

PHONE INSTALLATION
Place these files on an HTTPS web host, open that HTTPS address on the phone, then install/add it to the Home Screen from the browser.

DATA
Timesheet entries remain local to the browser/app profile. Use Save backup to export timesheet-data.json and Load JSON to restore or move entries.
