# MyDay Android-ready PWA

This is a free, installable web app package for MyDay. It includes a daily task planner, habits, a focus timer, a daily review, local storage, data export/import, an "Up Next" schedule panel, meal planning, water tracking, sleep/activity/mood check-ins, and health notes.

## Install on Android (free)
A Progressive Web App must be served from an HTTPS website to install properly. Opening `index.html` directly from Downloads is useful for testing, but will not enable full installation/offline features.

1. Upload the contents of this folder to a free static host that supports HTTPS (for example, GitHub Pages).
2. Open the published HTTPS link in Chrome on your Android phone.
3. Open Chrome's menu (⋮), then choose **Install app** or **Add to Home screen**.
4. Launch MyDay from your home screen.

## Important reminder limitation
The first version can show browser notifications for scheduled tasks while the app is open and notification permission is granted. Android may pause browser tabs, and this version does not guarantee exact reminders when the app is closed. Reliable background reminders require a native Android implementation or a more advanced push-notification setup.

## Privacy and backups
Task and habit data is stored locally in the browser. It is not sent to a server by this app. Use Review → Export backup to save a JSON backup. Clearing browser data can erase the local copy.

## Contents
- `index.html` — app
- `manifest.webmanifest` — install metadata
- `sw.js` — offline app shell
- `icon-192.png`, `icon-512.png` — app icons
