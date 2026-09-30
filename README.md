# IMPORTANT DATA — PWA Install (GitHub Pages)

Secure local vault by **AJEET PARMAR**.

## Files (sab upload karo)

- `index.html` — main app
- `manifest.webmanifest` — install metadata
- `sw.js` — service worker
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — app icons

**Mat upload karo:** passwords, `.vault` backup, PDF exports (personal data).

## GitHub pe kaise dalein

1. GitHub pe naya repository banao (Public OK for code; Private bhi chalega)
2. Ye **saari files** repo root mein upload karo (drag & drop ya git push)
3. Repo → **Settings** → **Pages**
4. Source: **Deploy from a branch**
5. Branch: **main** (or master), folder: **/ (root)**
6. Save — 1–2 minute wait
7. Link milega: `https://YOUR_USERNAME.github.io/REPO_NAME/`

## Mobile pe Install

1. Chrome se upar wala **HTTPS link** open karo
2. **⋮** menu → **Install app** / **Add to Home screen**
3. Ya Settings tab mein **Install App** button (jab Chrome prompt de)

Local `file://` / `content://` pe Install option **nahi** aata — sirf HTTPS (GitHub Pages) pe aata hai.

## Data safety

- GitHub pe sirf **code** jaata hai
- Aapka data phone browser (IndexedDB) mein encrypted rehta hai
- Strong master password use karo

## Safety tips

1. **SRI** — `jspdf` script pe integrity hash laga hai (tamper block).
2. **`.gitignore`** — `.vault`, PDF, backups commit nahi honge.
3. **Strong master password** — 14–16+ chars, mix of letters/numbers/symbols.
4. **Repo Private** optional — code privacy ke liye; data phir bhi phone pe hi rehta hai.
5. GitHub pe **kabhi mat daalo**: password, `.vault`, export PDF, real screenshots.
