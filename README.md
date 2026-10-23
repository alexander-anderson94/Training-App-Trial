# Training App: installable version

A self-contained training log you can install on a phone or computer. It works offline, saves everything on the device, and has nothing to sign up for.

## What's in the folder

| File | What it does |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Lets phones and browsers install it as an app (name, icon, colours) |
| `sw.js` | Keeps it working offline |
| `icon-192.png`, `icon-512.png`, `maskable-512.png`, `apple-touch-icon.png` | Home-screen icons |

Keep the files together in one folder. To install, a browser needs the app on an **https** web address. Opening `index.html` straight from your files works for a quick look, but it won't install or work offline that way.

## Put it online (free, about 5 minutes)

### Option A: GitHub Pages
1. Sign in at github.com and create a new **public** repository, e.g. `training-app`.
2. On the repository page, choose **Add file → Upload files** and drag in everything from this folder, all at the top level, with no folders. Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, pick **main** and **/(root)**, then Save.
4. After a minute the address appears at the top of that page, e.g. `https://yourname.github.io/training-app/`.

### Option B: Netlify
1. Sign in at app.netlify.com (free account).
2. Choose **Add new site → Deploy manually** and drag this folder onto the page.
3. You get an address like `https://something.netlify.app`. You can rename it in Site settings.

To update the app later, upload the new files the same way. People who have installed it get the update the next time they open it while online.

## Install it

- **iPhone or iPad:** open the address in **Safari**, tap **Share**, then **Add to Home Screen**.
- **Android:** open it in **Chrome** and tap **Install app** (from the browser menu, or the app's own menu, where it appears under Help & settings).
- **Mac or PC:** in Chrome or Edge, click the install icon in the address bar.

## Your data

- Everything is saved on the device it's used on. Nothing is sent anywhere.
- **Back up** from the menu: **Backup & data → Download full backup**. Load that file on another device with **Import** to carry your log across.
- **Share a programme** with **Download templates only**. The other person imports the file and starts their own run of it.
- Installed apps keep their data. In a normal browser tab, especially Safari, clearing website data deletes it, so install the app or back up regularly.

## For testers

1. Open the menu, tap **User guide**, and skim "Getting around".
2. Set your maxes when the welcome card asks.
3. Use **Feedback** in the menu to note anything confusing, missing or broken as you go, then tap **Copy notes** or **Download as text** to send it back.
