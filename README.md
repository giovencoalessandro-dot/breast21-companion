# Breast21 Companion MVP

Offline-first PWA demo for Breast21 first customer meetings.

## What is included
- Dashboard
- One-question-at-a-time guided interview
- Automatic Branch A / Branch B logic
- Searchable offline FAQ and internal field notes
- Capture of new/unanswered customer questions
- Saved snapshots on the device
- TXT, JSON and CSV export

## How to test locally
Open `index.html` in a browser. For full offline/PWA behavior, host the folder on HTTPS.

## Recommended SharePoint / Teams deployment
1. Unzip this package.
2. Upload the full `Breast21_Companion_MVP` folder to a SharePoint document library or Teams files area.
3. Open `index.html` from SharePoint in the browser.
4. On iPad/iPhone, open the link in Safari and use Share → Add to Home Screen.
5. Open the app once while online. After that, the app shell and content are cached for offline use.

## Important MVP limitation
Interview data is saved locally on the specific device. It is not automatically synced to SharePoint in this MVP.
Users should export TXT/JSON/CSV files and upload them to the team folder when needed.
