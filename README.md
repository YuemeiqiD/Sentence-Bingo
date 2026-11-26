# Sentence Bingo — 日本語作文ビンゴ

A Japanese sentence-writing bingo app. It stores cards in this browser's local storage; export a JSON backup regularly if you want to keep your data.

## Publish on GitHub Pages

Upload **all files in this folder** to the repository root (not the folder itself), then commit. In GitHub Pages settings, publish the `main` branch from `/ (root)`.

## Install on Android Chrome

1. Open the published HTTPS GitHub Pages URL in Chrome.
2. Open Chrome's ⋮ menu.
3. Choose **Install app** (or **Add to Home screen**, depending on Chrome version).
4. Confirm. The app opens in a standalone window from the home-screen icon.

The site includes a web app manifest and service worker for installation and offline app-shell/audio caching. The first visit needs an internet connection.

## Files

Keep `index.html`, `manifest.webmanifest`, `sw.js`, the icons, and the three MP3 files together at the repository root. The app uses relative paths so it works from a GitHub Pages project site.
