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

## AdMob verification

Keep `app-ads.txt` at the repository root so GitHub Pages serves it at
https://discvault.us/app-ads.txt. Preserve this file when replacing the static export.
Its seller record must match the personalized snippet from AdMob's **Apps → View
all apps → app-ads.txt → How to set up app-ads.txt** page.

After pushing to `main`, check that the URL displays the plain-text seller record.
Set `https://discvault.us` as the developer website in the Google Play store listing.
Once the app can be linked in AdMob, use **Verify app → Check for updates**;
Google says crawling and verification can take up to 24 hours.
See [Google's setup instructions](https://support.google.com/admob/answer/9363762?hl=en).
