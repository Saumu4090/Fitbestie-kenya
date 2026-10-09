# FitBestie Kenya — Version 1

A lightweight, offline-first Kenyan food and fitness diary.

## Run it now
- Open `index.html` in a modern browser to try the interface. Browser restrictions may prevent installation/offline caching when opened directly as a file.
- Your entries are stored in that browser's local storage on that device. Use **Settings & backup → Export backup** regularly.

## Install it as an app on Android (PWA)
A PWA must be served over HTTPS (or localhost) for service workers and reliable installability. Do not just open the HTML file from Downloads if you want full PWA installation.

### Easiest hosting route: GitHub Pages
1. On a computer (or a phone browser in desktop mode), sign in to GitHub and create a **public** repository, e.g. `fitbestie-kenya`.
2. Upload all files in this folder to the repository's root (`index.html`, `manifest.json`, `sw.js`, and both SVG icons).
3. In the repository, open **Settings → Pages**. Choose deployment from the `main` branch and the root folder, then save.
4. Wait for GitHub Pages to publish the HTTPS site. Open the published URL on your Infinix in Chrome while online.
5. Let the page finish loading once. Open Chrome's three-dot menu and choose **Install app** or **Add to Home screen** (wording may vary). Confirm.
6. Open FitBestie from its new home-screen icon. After the first successful load, the app shell is cached for offline use.

## Data & privacy
- No account, analytics, or external food API is used by this app.
- Diary data is saved in browser local storage and does not sync across devices.
- Export a JSON backup before clearing browser data or changing phones. Importing a backup replaces current tracker data.
- If browser storage is cleared, data may be lost.

## Starter nutrition data
Food values are broad estimates for typical portions and recipes, not authoritative nutrition-label values. Calorie and protein values can vary substantially with oil, ingredients, brands, and serving size. Replace them with package labels or a reliable nutrition database where possible.

## Current version
Includes food search, small/medium/large/listed portions, meal logging, calorie/protein totals, editable daily targets, water log, steps, movement notes, workout log, weight/waist/hip check-ins, local persistence, and JSON backup/import.
