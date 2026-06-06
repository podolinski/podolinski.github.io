# podolinski.com

Personal website of Georgi Podolinski — Open Source Program Office (OSPO) Leader.

🌐 **Live at [podolinski.com](https://podolinski.com)**

---

## About

A single-page personal portfolio site showcasing open source governance experience, career achievements, and focus areas. Built to serve as a consistent identity alongside the CV and LinkedIn profile.

## Stack

- **Pure HTML/CSS/JS** — no frameworks, no build step, no dependencies
- **Hosted on** GitHub Pages
- **Analytics** — Google Analytics 4 (cookieless, privacy-friendly mode)
- **Fonts** — EB Garamond + DM Mono via Google Fonts

## Structure

```
podolinski.github.io/
└── index.html      # The entire site — self-contained, all assets inline
```

The site is intentionally a single self-contained file. The photo and CV PDF are embedded as base64 data URIs so there are no external file dependencies to manage.

## Updating the site

1. Edit `index.html`
2. Commit and push to the `main` branch
3. GitHub Pages deploys automatically — live within ~60 seconds

## Custom domain

The site is served from `podolinski.com` via a custom domain configured in **Settings → Pages**. DNS is managed through SuperHosting with four GitHub Pages A records pointing to `185.199.108–111.153` and a `www` CNAME to `podolinski.github.io`.

## Analytics

GA4 Measurement ID: `G-PFEKYJJ0NH`  
Configured in cookieless mode (`storage: none`, `anonymize_ip: true`) — no cookie consent banner required.

## License

© 2026 Georgi Podolinski. All rights reserved.
