# Training App: installable version

A self-contained training log you can install on a phone or computer. It works offline, saves everything on the device, and has nothing to sign up for.

## What's in the folder

| File | What it does |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets phones and browsers install it as an app (name, icon, colours) |
| `sw.js` | Keeps it working offline |
| `icon-192.png`, `icon-512.png`, `maskable-512.png`, `apple-touch-icon.png` | Home-screen icons |

Keep the files together. A browser can only install the app from an **https** web address. Opening `index.html` straight from your files works for a quick look, but it won't install or work offline that way.

## Put it online (free, about 5 minutes)

### Option A: GitHub Pages
1. Sign in at github.com and create a new **public** repository, e.g. `training-app`.
2. Choose **Add file → Upload files** (or "uploading an existing file" on an empty repository) and add everything from this folder. Commit.
3. Go to **Settings → Pages**. Set Source to **Deploy from a branch**, then pick **main** and **/(root)**. Save.
4. After a minute the address appears at the top of that page, e.g. `https://yourname.github.io/training-app/`.

### Option B: Netlify
1. Sign in at app.netlify.com (free account).
2. Choose **Add new site → Deploy manually** and drag this folder onto the page.

To update, upload the new files the same way. Installed copies update the next time they're opened online.

## Install it

- **iPhone or iPad:** open the address in **Safari**, tap **Share**, then **Add to Home Screen**.
- **Android:** open it in **Chrome**, then tap **Install app** from the browser menu or the app's own menu.
- **Mac or PC:** in Chrome or Edge, use the install icon in the address bar.

## Your data

- Everything is saved on the device it's used on. Nothing is sent anywhere.
- **Back up** from the menu with **Backup & data → Download full backup**. Load that file on another device with **Import**.
- **Share a programme** with **Download templates only**. The other person imports it and starts their own run.
- Install the app rather than using a browser tab. Safari can clear data for websites that aren't on the Home Screen.

## For testers

1. In the menu, open **User guide** and skim "Getting around".
2. Set your maxes when the welcome card asks.
3. Use **Feedback** in the menu to note anything confusing, missing or broken, then **Copy notes** or **Download as text** to send it back.
