# COREX · Mobile stable v5 (20261023-05)

## Why the earlier mobile version was unreliable
- The GitHub Pages package uses a separate `corex-demo.html` route on phones. If only `index.html` was uploaded, a mobile click could go to a missing file while the desktop demo still worked inline.
- The single-file edition formerly used `blob:` navigation for the mobile demo. Safari and iOS file previews can restrict those URLs.
- The menu depended on JavaScript instead of the browser's native `<details>` interaction.

## Fixes in v5
- Touch-friendly **native mobile menu**, functioning without JavaScript.
- Full GitHub package: normal navigation to the included `corex-demo.html` (no popup/iframe on mobile).
- Standalone: loads the embedded live app in-place (no extra files, popups or blob URLs).
- Safer slide `history.replaceState` behavior on offline/file origins.
- Visible footer version `Mobile build 20261023-05` to confirm deployment is updated.

## IMPORTANT PUBLISHING
**Recommended:** Use everything inside the ZIP, not only `index.html`.
Files `index.html`, `corex-demo.html`, `assets/`, and `COREX_Presentation.pdf` belong together at the repository root.
In Settings → Pages use main / (root).
After publishing verify you see **Mobile build 20261023-05** in the footer. If not, the old site is being displayed or the upload hasn't deployed yet. Do a private-window reload or add `?v=20261023-05` at the end of the site URL.

If you upload only a single HTML file, rename **COREX_Mobile_Stable_STANDALONE_v5.html** to `index.html` before pushing; do not also upload a second `index.html`.

Real iPhone/Safari hardware verification has not been performed in this environment; automated tap checks are on emulated mobile Chromium.
