# josholiver.github.io

Personal portfolio site for **Oliver Joshua Jacob** — Google Ads Manager & Performance Marketing Specialist at Tide Rock, New Delhi YMCA Board of Directors member, and long-distance cyclist.

🔗 **Live site:** [josholiver.github.io](https://josholiver.github.io/)

## About

This is a single-page portfolio covering:
- **About** — background, credentials (Google Digital Guru, Executive MBA in progress), and current role
- **Resume** — work experience, education, a dedicated Leadership & Community section, skills, certifications, and honors
- **Selected Experience** — companies worked with, grouped as Current / Previous / Earlier
- **Media & Recognition** — press coverage, leadership roles, and cycling achievements
- **Contact** — how to get in touch

## Tech stack

Static site — no build step, no framework, no backend.

- HTML5 / CSS3 / vanilla JS
- jQuery (DOM handling, form validation, popups)
- [particles.js](https://github.com/VincentGarreau/particles.js/) — animated hero background
- [Magnific Popup](https://dimsemenov.com/plugins/magnific-popup/) — image/media lightbox
- [Masonry](https://masonry.desandro.com/) + a custom filter script — the tag-filterable Media & Recognition grid
- [SimpleBar](https://github.com/Grsmto/simplebar) — custom scrollbars within each card
- [Typed.js](https://github.com/mattboldt/typed.js/) — the rotating hero tagline
- Google Analytics (gtag.js)

## Structure

```
├── index.html              # the entire site — single page, sectioned by <div class="card-inner">
├── css/                     # theme stylesheets (layout, colors, icon font)
├── js/                      # jQuery + the plugins listed above
├── fonts/                   # Line Awesome icon font
├── images/
│   ├── clients/             # company logos shown in Selected Experience
│   └── ...                  # profile photos, background images, work samples
├── mailer/                  # legacy PHP contact-form handler (inactive — GitHub Pages is static hosting)
├── robots.txt
└── sitemap.xml
```

## SEO / discoverability

- `robots.txt` and `sitemap.xml` for search engine crawling
- Canonical URL tag
- Open Graph meta tags (clean previews when shared on LinkedIn, WhatsApp, etc.)
- `Person` schema (JSON-LD) for structured data

## Updating this site

Everything lives in `index.html` — there's no CMS or build process. To update:
1. Edit `index.html` directly (or download, edit locally, re-upload).
2. Add any new logos/photos into the relevant `images/` subfolder.
3. Commit to `main` — GitHub Pages redeploys automatically within about a minute.

## Contact

- LinkedIn: [josh-oliver](https://www.linkedin.com/in/josh-oliver/)
- Email: oliverdgr888@gmail.com
