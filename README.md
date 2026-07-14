# animacy-preview

Standalone live-preview staging for [Animacy] — served via GitHub Pages.

Everything the app needs lives in this repo: text assets as-is, every binary as base64
text under `assets-b64/` (the build agent's git access is text-only). Small textures
preload at boot; hero models lazy-decode on first selection. Voice runs the offline
demo brain — typing works.

**Enable once:** Settings → Pages → Deploy from a branch → `main` / `(root)`.
**URL:** https://arkangel2k4.github.io/animacy-preview/

Pushed by the Animacy build agent; refreshed on request. Disposable staging — the
source of truth is the private Animacy repo.
