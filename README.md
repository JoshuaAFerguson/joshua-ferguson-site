# Joshua Ferguson Professional Entity Hub

Static personal-professional website scaffold for `joshua-ferguson.com`.

## Purpose

This site is designed as the canonical professional identity hub for Joshua Ferguson, separate from personal or pseudonymous profiles. It gives search engines, LLMs, journalists, investors, and partners a clear source of truth connecting Joshua Ferguson to VeriSwarm and related professional work.

## Included

- Static HTML pages
- Responsive CSS
- Basic JavaScript for footer year
- `Person` schema JSON-LD on the homepage
- GitHub Pages deployment workflow
- Sitemap and robots.txt
- Professional-only outbound links

## Pages

- `index.html` — homepage and primary entity signal
- `about.html` — professional biography
- `projects.html` — VeriSwarm and public work
- `writing.html` — future essays and commentary
- `speaking.html` — speaking topics and appearances
- `press.html` — press kit starter
- `contact.html` — professional links

## Before Publishing

1. Replace placeholder text where desired.
2. Add a professional headshot to `assets/img/` and reference it in schema.
3. Confirm all canonical URLs match your final domain.
4. Add additional professional `sameAs` links only if they are meant to be associated with Joshua Ferguson professionally.
5. Keep personal/pseudonymous accounts separate.

## Deployment

This repository includes a GitHub Pages workflow. Push to `main`, enable GitHub Pages using GitHub Actions, and configure the custom domain `joshua-ferguson.com`.
