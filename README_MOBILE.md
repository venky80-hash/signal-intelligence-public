# SIGNAL Intelligence – iPhone Edition

A mobile-first, installable web-app starter. It stores manually entered intelligence signals and action items in local browser storage.

## Files
- index.html – mobile dashboard, signal form, competitor directory, action tracker, backup/restore
- manifest.webmanifest – install metadata
- sw.js – offline cache
- icon.svg – app icon

## Important
This is a static PWA. It does not crawl the web or automatically sync with ChatGPT or Notion yet.

## Publish for iPhone Home Screen installation
The PWA must be served over HTTPS. One free route is GitHub Pages:
1. Upload these files to the repository root.
2. Enable Settings > Pages > Deploy from branch > main > /(root).
3. Open the published HTTPS site in Safari on iPhone.
4. Tap Share > Add to Home Screen > Add.
5. Launch SIGNAL from the new Home Screen icon.

Keep backups: the starter stores data in the browser on the device. Export JSON regularly.
