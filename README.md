# Dubai Formation LP

Dedicated single-page repository for the Rise Accounting Dubai Formation landing page.

## Purpose

This repo serves ONE page: Dubai Formation. It is deployed to `lp.riseaccounting.ae` (subdomain of riseaccounting.ae) so that same-site cookies work when the page is embedded in the Framer-wrapped `riseaccounting.ae/dubai-formation` URL. This fixes HubSpot ad attribution for Meta ad traffic.

## Live URLs

- Public GitHub Pages URL: `https://the-rise-group.github.io/dubai-formation-lp/dubai-formation/`
- Custom domain (after DNS CNAME added): `https://lp.riseaccounting.ae/dubai-formation/`

## Structure

```
.
├── CNAME                       Custom domain for GitHub Pages
├── dubai-formation/
│   └── index.html              The Dubai Formation landing page
└── assets/                     Images, fonts, logos referenced by the page
    ├── hero-dubai-4k.jpg
    ├── font-*.woff2
    ├── logo-*.svg
    ├── img-*.webp              Review headshots and photos
    └── ...
```

## Why hard isolation

Only the Dubai Formation page lives here. No other LP pages are accessible via this subdomain. The multi-page repo at `The-Rise-Group/riseaccountingdubai` serves the other LP pages separately.

## Source

Mirrored from `go4shubham/rise-accounting-lp` and `The-Rise-Group/riseaccountingdubai` as of 2026-10-08. Future updates land on this repo directly.
