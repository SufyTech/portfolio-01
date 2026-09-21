# Favicon — Sufiyan Khan portfolio

Monogram mark built from your site's own palette (bone `#faf8f2`, ink `#171614`,
terracotta `#9e421f`) and a serif letterform matching the Playfair Display
feel of the site.

## 1. Add these files to your repo
Drop every file in this zip into the **same folder as `index.html`** (the repo root).

## 2. Paste this into `<head>`
Add it right after your existing `<title>` / meta tags, before the Google Fonts `<link>`:

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="manifest" href="/site.webmanifest">
<meta name="theme-color" content="#faf8f2">
```

## 3. Push to GitHub
From your local repo folder (with the new files copied in and the `<head>` edited):

```bash
git add favicon.ico favicon.svg favicon-16x16.png favicon-32x32.png apple-touch-icon.png android-chrome-192x192.png android-chrome-512x512.png site.webmanifest index.html
git commit -m "Add favicon"
git push
```

If your site auto-deploys (Vercel/Netlify/GitHub Pages), the push alone triggers a new
build — nothing else to do. Hard-refresh (Ctrl/Cmd+Shift+R) once it's live; browsers
cache favicons aggressively.

## Files in this zip
- `favicon.ico` — multi-size (16/32/48px) fallback for old browsers
- `favicon.svg` — crisp vector version modern browsers prefer
- `favicon-16x16.png`, `favicon-32x32.png` — PNG fallbacks
- `apple-touch-icon.png` — 180×180, iOS home-screen icon
- `android-chrome-192x192.png`, `android-chrome-512x512.png` — Android/PWA icons
- `site.webmanifest` — references the Android icons above
