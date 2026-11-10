# Fish Business Orders PWA

This is a Progressive Web App shell for the existing Google Apps Script customer order form. The Google Apps Script deployment remains the order-processing backend; the payment manager and spreadsheet are not included in this public repository.

## Publish with GitHub Pages
1. Upload all files and the `icons` folder to the repository root on the `main` branch.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. Wait for GitHub Pages to publish. The site URL should be `https://miggzmatt.github.io/fish-business-orders/`.

## Install
- Android: open the Pages URL in Chrome and choose **Install app** or **Add to Home screen**.
- iPhone: open the Pages URL in Safari, tap Share, then **Add to Home Screen**.

## Important behavior
The PWA shell can cache its own static files, but order submission still requires an internet connection and the Google Apps Script service. The form is displayed in an iframe to preserve the current `google.script.run` integration.
