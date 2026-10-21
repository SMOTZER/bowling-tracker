# Bowling Tracker

An installable web app for season-by-season bowling scoresheets. Plain HTML, no build step.

## Put it on GitHub Pages
```bash
cd bowling-app
git init -b main
git add .
git commit -m "Bowling Tracker"
git remote add origin https://github.com/SMOTZER/bowling-tracker.git
git push -u origin main
```
Then on GitHub: Settings > Pages > Build and deployment > Deploy from a branch > `main` / `/ (root)` > Save.
The app will be at `https://smotzer.github.io/bowling-tracker/` after a minute or two.

## Install on your phone
- iPhone: open the link in Safari, tap Share, then Add to Home Screen.
- Android: open the link in Chrome, tap the menu, then Install app.

## Your data
Scores are stored on the device you type them on. Nothing is uploaded, and phone and laptop do not sync.
Use **Back up** to save a JSON file and **Restore** to load it on another device or after clearing browser data.

## Updating
Edit `index.html`, then change `CACHE` in `sw.js` (for example to `bowling-tracker-v2`) so installed copies update.
