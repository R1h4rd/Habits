# Habits

A simple habit tracker that installs on your phone as an app. Build good habits, quit bad ones. Works offline.

## Put it online with GitHub Pages

1. Create a new repository on GitHub (for example `habits`).
2. Upload everything in this folder, keeping the `icons` folder as it is.
3. In the repository, go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute the app is live at `https://<your-username>.github.io/habits/`.

## Install it on your phone

- **Android (Chrome):** open the link, tap the **⋮** menu → **Add to home screen** / **Install app**.
- **iPhone (Safari):** open the link, tap **Share** → **Add to Home Screen**.

It then opens full screen from its own icon, and works without a connection.

## Your data

Habits are stored on your phone, inside the installed app. Nothing is sent anywhere.
Use the **⋯** button to save a backup file now and then, and to restore it on a new phone.

## Updating the app

After changing any file, open `sw.js` and bump `VERSION` (for example `'v1'` → `'v2'`).
Phones pick up the new version the next time the app is opened online.
