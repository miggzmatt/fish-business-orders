# Fish Business Orders PWA

A small installable home-screen app that opens the existing Google Apps Script customer order form in a separate browser tab. It does not embed the Apps Script page, and it does not include the spreadsheet or payment manager.

## Publish with GitHub Pages
1. Upload/replace the files and the `icons` folder in the repository root on `main`.
2. In GitHub, open **Settings → Pages**.
3. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. Open `https://miggzmatt.github.io/fish-business-orders/`.

## Install
- Android: open the Pages URL in Chrome and choose **Install app** or **Add to Home screen**.
- iPhone: open the Pages URL in Safari, tap Share, then **Add to Home Screen**.

## Notes
The PWA launcher can load offline after its shell has been cached, but placing an order requires internet access and the Google Apps Script service. The Google Apps Script backend remains unchanged.
