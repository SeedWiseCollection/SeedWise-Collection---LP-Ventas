# Seedwise — Sales Landing Page

Sales landing page for The Seedwise Collection: four age-by-age ebook volumes (Ages 3–18) that help parents raise financially confident children.

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/seedwise-landing)

1. Push this repo to GitHub
2. Connect the repo in [Vercel Dashboard](https://vercel.com/new)
3. Deploy — no build step needed (static HTML)

## Project Structure

```
seedwise-landing/
├── index.html          # Landing page (55KB)
├── vercel.json         # Cache headers + security
├── robots.txt          # Search engine directives
├── sitemap.xml         # SEO sitemap
├── README.md
└── images/
    ├── cover-first-seeds.jpg
    ├── cover-growing-roots.jpg
    ├── cover-wings-to-decide.jpg
    └── cover-taking-flight.jpg
```

## Performance

- **HTML**: ~55KB (down from 425KB with inline base64)
- **Images**: served separately with `immutable` cache headers (1 year)
- **Fonts**: Google Fonts with `preconnect` + `font-display: swap`
- **Above-the-fold images**: preloaded via `<link rel="preload">`
- **Below-the-fold images**: `loading="lazy"` with explicit `width`/`height`
- **Animations**: respect `prefers-reduced-motion`

## Brand

| Color           | HEX       | Usage              |
|-----------------|-----------|-------------------|
| Dark Base       | `#1A1F2B` | Page background   |
| Deep Teal       | `#1A5F5A` | Titles            |
| Almond White    | `#F7F3E8` | Text on dark      |
| Horizon Orange  | `#E3655B` | CTAs              |
| Growth Green    | `#49A078` | Accents           |
| Warm Gold       | `#C9A96E` | Labels / details  |

Fonts: **Lora** (serif, headlines) · **DM Sans** (sans-serif, body)

## Before Going Live

1. Replace `https://seedwise.com` in meta tags with your actual domain
2. Add your payment links to all CTA `href="#"` buttons
3. Replace placeholder sneak-peek images with real interior page screenshots
4. Verify OG image path matches your domain

---

© 2026 Seedwise — Financial Wisdom Collection
