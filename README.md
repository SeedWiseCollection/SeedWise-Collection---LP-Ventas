# SeedWise Collection — Sales Landing Page

High-conversion sales landing page for **The SeedWise Collection**: four age-by-age ebook volumes (Ages 3–18+) that help parents raise financially confident children.

## Deploy to Vercel

1. Push this repo to GitHub
2. Connect the repo in [Vercel Dashboard](https://vercel.com/new)
3. Deploy — no build step needed (static HTML)

## Project Structure

```
seedwise-landing/
├── index.html          # Sales landing page
├── thank-you.html      # Post-purchase confirmation
├── terms.html          # Terms & Conditions
├── privacy.html        # Privacy Policy
├── cookies.html        # Cookies Policy
├── vercel.json         # Cache headers, security, clean URLs
├── robots.txt          # Search engine directives
├── sitemap.xml         # SEO sitemap
├── README.md
└── images/
    ├── hero-collection.jpg
    ├── collection-lineup.jpg
    ├── mockup-first-seeds.jpg
    ├── mockup-growing-roots.jpg
    ├── mockup-wings-to-decide.jpg
    ├── mockup-taking-flight.jpg
    ├── Image_1-Flight_Plan_to_my_dreams.jpg
    ├── Image_2-_The_50_30_20_Rule.jpg
    └── Image_3_-Teen_Budget_expense_Tracker.PNG
```

## Performance

- **Static HTML** — zero build step, instant deploy
- **Images**: served with `immutable` cache headers (1 year)
- **Fonts**: Google Fonts with `preconnect` + `font-display: swap`
- **Above-the-fold images**: preloaded via `<link rel="preload">`
- **Below-the-fold images**: `loading="lazy"` with explicit `width`/`height`
- **Animations**: respect `prefers-reduced-motion`
- **Security**: HSTS, X-Frame-Options DENY, CSP headers via Vercel

## Brand System

| Color           | HEX       | Usage                |
|-----------------|-----------|----------------------|
| Dark Base       | `#1A1F2B` | Page background      |
| Dark Surface    | `#222738` | Card backgrounds     |
| Dark Elevated   | `#2A2F42` | Elevated elements    |
| Almond White    | `#F7F3E8` | Primary text         |
| Deep Teal       | `#1A5F5A` | Authority accents    |
| Growth Green    | `#49A078` | Positive indicators  |
| Horizon Orange  | `#E3655B` | CTAs only            |
| Warm Gold       | `#C9A96E` | Labels / details     |

**Fonts**: Plus Jakarta Sans (headlines) · Source Serif 4 (body)

## Third-Party Integrations

- **Gumroad** — Payment processing + digital delivery
- **MailerLite** — Email capture (lead magnet form)
- **Google Fonts** — Typography

## Before Going Live

1. Verify all Gumroad product links are correct
2. Confirm MailerLite form ID (`Odqgfa`) matches your account
3. Test checkout flow end-to-end (desktop + mobile)
4. Verify OG image loads at `https://seedwisecollection.com/images/hero-collection.jpg`

---

© 2026 SeedWise Collection
