# SEC-APAC-MB Product Documentation

Static docs site for SEC-APAC-MB cybersecurity products.

## Products

- **Vigilar** — On-device security companion (macOS, Android). Real-time threat monitoring, AI chat, breach alerts.
- **ARCZT Personal Vault** — Zero-knowledge, quantum-resistant credential manager.

## Structure

```
├── index.html              ← Landing page (company overview + product cards + interest form)
├── _config.yml             ← Jekyll/GitHub Pages config
├── assets/
│   ├── styles.css          ← All styling (dark theme, responsive)
│   ├── form.css            ← Interest form styles
│   └── favicon.svg         ← Shield + flame logo
├── about/
│   └── index.html          ← About page
├── products/
│   ├── index.html           ← Products overview
│   ├── vigilar/index.html   ← Vigilar product page
│   └── arczt-vault/index.html ← ARCZT Vault product page
├── docs/
│   ├── index.html           ← Docs landing (links to all sub-pages)
│   ├── vigilar/
│   │   ├── features/index.html
│   │   ├── security/index.html
│   │   ├── install/index.html
│   │   ├── pricing/index.html
│   │   └── faq/index.html
│   └── arczt-vault/
│       ├── features/index.html
│       ├── security/index.html
│       ├── install/index.html
│       ├── pricing/index.html
│       └── faq/index.html
└── README.md
```

## GitHub Repos

- **Org**: https://github.com/SEC-APAC-MB
- **This site**: https://github.com/SEC-APAC-MB/sec-apac-mb.github.io
- **Vigilar app**: https://github.com/SEC-APAC-MB/vigilar-app
- **ARCZT Vault**: Source coming soon — see org page for updates

## Deploy

This is a static site hosted on GitHub Pages. Push to the `main` branch of
`SEC-APAC-MB/sec-apac-mb.github.io` and GitHub Pages auto-deploys.

## Conventions

- All pages include: canonical URL, nav with "Request Test Build" CTA, consistent footer
- Docs pages include: "View source on GitHub" and "Edit this page on GitHub" links at bottom
- Sidebar links use no trailing slashes (e.g., `/docs/vigilar/features` not `/docs/vigilar/features/`)
- ARCZT Vault GitHub links point to org page (repo doesn't exist yet)