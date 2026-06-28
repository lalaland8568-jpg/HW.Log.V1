# H.W. Log Workout Tracker

A polished, mobile-friendly workout tracking web app built as a static site/PWA. It includes a PIN screen, workout logging, profile-style UI, and offline-friendly behavior through a service worker.

## Features
- PIN-protected access
- Workout logging experience for daily training
- Mobile-friendly layout for phones
- Progressive Web App support
- Offline caching via service worker

## Run locally
1. Open the project folder in a browser, or serve it locally with Python:
   ```bash
   python -m http.server 8000
   ```
2. Visit http://127.0.0.1:8000/

## Publish to GitHub Pages
This project is ready to be published as a static site.

1. Push the repository to GitHub.
2. In GitHub, open the repository settings and enable GitHub Pages.
3. Choose the branch to publish from (usually `gh-pages` or `main`).
4. Save the settings and wait for the site to build.

## Files to know
- index.html — main app UI
- manifest.json — PWA manifest
- sw.js — service worker for offline caching
