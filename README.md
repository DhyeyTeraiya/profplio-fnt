# 🎨 Portfolio Website — Static Front-end

A single-page portfolio site built as plain **HTML / CSS / JavaScript** with no
build step. `index.html` is self-contained and everything it needs lives in
`assets/`.

## Structure

```text
.
├── index.html      # the whole page (inlined styles/scripts)
└── assets/         # images, icons, fonts
```

## Run it

No tooling required — open `index.html` directly, or serve the folder:

```bash
python -m http.server 8000   # http://localhost:8000
```

## Deploy

Drop the folder on any static host — GitHub Pages, Netlify, Vercel or
Cloudflare Pages. No build configuration needed.

## Before publishing

- The `<title>` still reads **"Harsh"**, left over from the theme this was built
  on — update it in `index.html`.
- Replace the placeholder copy and the images in `assets/` with your own.
- The page is one large inlined file; if you plan to keep extending it, split
  the CSS and JS into `assets/` and link them instead.
