# Galaxy Apps — Official Website (`galaxy-apps.com`)

Official product website for **Galaxy Apps**, an independent Shopify app studio based in Hanoi, Vietnam.

## Live Products on the Shopify App Store

- **[ThemeSafe ‑ Security ‑ Review](https://apps.shopify.com/themesafe-security)** — Rule-based detection combined with AI-powered security code review and real-time change monitoring for Shopify themes.
- **[ThemeSafe ‑ Auto Backup](https://apps.shopify.com/theme-backup-1)** — Automated scheduled backups and one-click recovery for Shopify themes and store assets.
- **[OrderSafe ‑ Auto Backup](https://apps.shopify.com/ordersafe-auto-backup)** — Real-time automated order backup to email and cloud storage.

## Architecture

- Zero-dependency static HTML5, modern CSS (`Plus Jakarta Sans` + `JetBrains Mono`, automatic Light/Dark mode), and vanilla JavaScript (`IntersectionObserver`).
- Hosted directly on GitHub Pages via [`CNAME`](./CNAME) (`galaxy-apps.com`).
- Pages:
  - [`index.html`](./index.html) — Main product landing page with `Organization` and `SoftwareApplication` JSON-LD structured data.
  - [`privacy.html`](./privacy.html) — Comprehensive Shopify API & GDPR/CCPA Privacy Policy with dedicated per-app sections (`#themesafe-security`, `#theme-backup`, `#ordersafe`).
