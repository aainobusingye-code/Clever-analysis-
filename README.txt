CLEVER ANALYSIS — FIRST PROTOTYPE

Files:
- index.html: responsive app interface and local prototype functionality
- manifest.json: installable web-app metadata
- sw.js: basic offline caching

IMPORTANT:
This is a front-end prototype, not a production service.
The two fixtures are samples and must be replaced with verified fixtures and analysis.
The Admin form saves only in the current browser/device using local storage.
There is no real user account system, shared database, secure admin authentication,
payment processing, or automatic premium unlocking yet.

To test:
1. Extract the ZIP.
2. Open index.html in a browser to preview (some PWA features require hosting).
3. To install as a PWA, upload the files to an HTTPS web host, open the site in Chrome,
   then use Chrome menu > Add to Home screen / Install app.

Next production steps:
- Choose domain and HTTPS hosting.
- Add secure backend/database and admin login.
- Connect a payment provider that supports MTN MoMo and Airtel Money in Uganda.
- Add payment verification and server-side premium access control.
