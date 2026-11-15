# Vinted Business Manager

A private installable web app (PWA) for tracking inventory, sales and net profit. The monthly net profit target defaults to £3,500.

## Publish it so you can install it on your phone
The app needs an HTTPS web address to install as an app. The simplest free option is GitHub Pages:

1. Sign in to GitHub or create an account.
2. Create a new **public** repository (for example `vinted-business-manager`).
3. Upload all four files in this folder to the repository's top level: `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg`.
4. In the repository, open **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for GitHub Pages to publish the site. Open the Pages URL it gives you using your phone.

## Add it to your phone
- **iPhone:** open the published URL in Safari → Share → Add to Home Screen.
- **Android:** open the published URL in Chrome → menu (⋮) → Install app / Add to Home screen.

## Important privacy and data notes
- This app stores records locally in the browser on the device where you use it. It has no account system, server database, Vinted integration or automatic cross-device sync.
- Do not put personal or sensitive information in item notes.
- Export a JSON backup regularly from Settings. Restoring a backup replaces the data currently on that device.
- GitHub Pages hosts the app files publicly, but your inventory and sales data are not uploaded to GitHub; they remain in local browser storage.
- For reliable use across multiple devices, you would need a private authenticated database/backend, which this starter version does not include.
