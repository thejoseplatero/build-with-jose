# Build with Jose

Landing page for Build with Jose — helping international product builders land their first North American PM role.

## Files

- `index.html` — the complete page (all CSS and JS are inline, no build step needed)

## Deploy

**Any static host works** — Netlify, Vercel, GitHub Pages, Squarespace, or plain FTP upload.

1. Upload `index.html` to your web host root (or drop the folder into Netlify/Vercel).
2. Done. The page is fully self-contained.

## Swap in a real founder photo

Find this comment in `index.html`:

```html
<!-- Replace SVG with <img src="jose.jpg" alt="Jose M."> when available -->
```

Replace the `<svg class="portrait-placeholder" ...>` block with:

```html
<img src="jose.jpg" alt="Jose M.">
```

Upload `jose.jpg` alongside `index.html`.

## Replace placeholder links

Search for `href="#"` to find nav links (Terms, Privacy, Twitter, LinkedIn) that need real URLs.

## Fonts

Loaded from Google Fonts CDN — Literata, Hanken Grotesk, JetBrains Mono. Requires an internet connection to render correctly. For offline/self-hosted use, download the font files and update the `<link>` tag in `<head>`.
