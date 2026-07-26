# NARRATA — AI Audiobook Narrator Studio

Installable PWA build of NARRATA v19 ("chat powers"). Turns documents into
narrated audiobooks, podcasts, comic strips, and cover art — entirely in the
browser, using your own Gemini / Deepgram API keys (stored locally on-device).

## Structure
- `index.html` — the whole app (single file)
- `manifest.webmanifest` — install metadata (name, icons, standalone display)
- `sw.js` — service worker: precaches the app shell + CDN libraries for offline use
- `icons/` — app icons (any + maskable + Apple touch)

## Install on a phone
Open the GitHub Pages URL in Chrome (Android) → menu ⋮ → **Add to Home screen / Install app**.
On iPhone: Safari → Share → **Add to Home Screen**.
