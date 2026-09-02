MY BUDDY — HOSTING READY

Recommended easiest route: GitHub Pages.
1. Create a GitHub repository named my-buddy.
2. Upload every file in this folder to the repository root.
3. Open repository Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Choose branch main and folder / (root), then Save.
6. GitHub will publish the site at a github.io address. It can take a few minutes.
7. Open the live address in Chrome on Android → ⋮ → Add to Home screen / Install app.

Alternative: Cloudflare Pages can deploy this static folder by Direct Upload or Git integration. No build command is required for this plain HTML app.

PWA:
- manifest.webmanifest and service worker are included.
- The app can open in standalone mode after installation.
- The service worker caches the app shell for repeat opening.

IMPORTANT:
This prototype stores financial data in browser localStorage. It is NOT suitable for shared/public financial data or production security yet.
Do not publish private statements, API keys, passwords, or personal financial records in the repository.
The document attachment UI is currently a prototype workflow; a real server-side PDF/OCR/XLSX/AI processor still needs to be connected.
