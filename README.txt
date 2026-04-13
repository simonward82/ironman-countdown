Ironman Countdown PWA Package

Files:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

How to use:
1. Upload all files to a simple static host.
2. Open the hosted URL in Chrome on Android.
3. Use the browser menu and choose Install app or Add to Home screen.

Good free hosting options:
- GitHub Pages
- Netlify
- Cloudflare Pages

Important:
- It needs to be served over HTTPS to install like an app.
- If you change the files later, you may need to refresh twice or clear the app cache because the service worker stores files offline.
