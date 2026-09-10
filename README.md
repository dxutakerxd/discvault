# DiscVault

Website for **DiscVault** — a local-first Android app for cataloging your DVD, Blu-ray and 4K movie
collection. Scan a barcode to catalog a disc, track every edition, and always know what to watch next.
Your collection stays on your device.

**Live at https://discvault.us**

## Hosting

GitHub Pages serves the prebuilt website directly from the root of `main`. Keep
`.nojekyll` so GitHub serves the generated `_next` assets without Jekyll processing.
No Node.js build or server is required for deployment.

`CNAME` retains the `discvault.us` domain. `download.html` redirects to the latest
APK on GitHub Releases. Existing FAQ, legal, and reference pages are retained.

The landing page includes the interactive 3D cases, app screenshots, the updated
DV logo, and scroll-controlled screening-room lighting. Its editable source is
maintained separately; the committed files here are the production static export.
