# Let's Date — PWA

Files:
- index.html — the complete app
- manifest.json — install/app metadata
- service-worker.js — offline app shell/cache
- icons/icon-192.png
- icons/icon-512.png

## Important
This version does NOT use Firebase or a database.

Request details are carried in the URL. The app needs to be hosted on HTTPS (for example GitHub Pages) for reliable PWA installation and service-worker support.

## GitHub Pages
1. Create a GitHub repository named `lets-date`.
2. Upload every file/folder from this ZIP, keeping the `icons` folder.
3. Enable GitHub Pages from the repository settings.
4. Open the resulting HTTPS site in Chrome.
5. Use Chrome's menu → Add to Home screen / Install app.

## WhatsApp
The app does not silently send WhatsApp messages. It prepares the message and opens WhatsApp Web; the user may need to press Send. The Copy Message button is provided as a fallback.

## Background images
The four habitat backgrounds are loaded from Unsplash URLs, so an internet connection may be needed for those images.
