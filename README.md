# SEC-APAC-MB Product Documentation

Static docs site for SEC-APAC-MB products.

## Structure

```
├── index.html              ← Landing page (company overview + product cards)
├── assets/
│   ├── styles.css          ← All styling (dark theme, responsive)
│   └── favicon.svg         ← Shield + flame logo
├── docs/
│   ├── vigilar/
│   │   └── index.html      ← Vigilar product docs
│   ├── arczt-vault/
│   │   └── index.html      ← ARCZT Vault product docs
│   └── ember-core/
│       └── index.html      ← Ember Core internal docs
└── README.md
```

## Deploy

This is a static site. Push to `SEC-APAC-MB/sec-apac-mb.github.io` repo and enable GitHub Pages.

## Add More Docs Pages

Each product has a sidebar with links to sub-pages (features, security, install, etc).
Create those pages as needed — they all use the same `assets/styles.css` and docs layout.