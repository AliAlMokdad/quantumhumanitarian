# Quantum Humanitarian — Book Website

Source for [quantumhumanitarian.ink](https://quantumhumanitarian.ink) — the book site for *Quantum Humanitarian: Witnessing the Fall, Holding What Remains, and Beginning the Rebuild* by Ali Al Mokdad (#1 Amazon Hot New Release in Philanthropy, Refugee Studies & Conflict Response, 2025).

## Live site

https://quantumhumanitarian.ink

## Languages

Available in 15 languages with full hreflang cross-referencing for international SEO:

| Code | Language | URL |
|---|---|---|
| en | English | [/](https://quantumhumanitarian.ink/) |
| fr | French | [/fr/](https://quantumhumanitarian.ink/fr/) |
| es | Spanish | [/es/](https://quantumhumanitarian.ink/es/) |
| de | German | [/de/](https://quantumhumanitarian.ink/de/) |
| no | Norwegian | [/no/](https://quantumhumanitarian.ink/no/) |
| ar | Arabic (RTL) | [/ar/](https://quantumhumanitarian.ink/ar/) |
| sv | Swedish | [/sv/](https://quantumhumanitarian.ink/sv/) |
| da | Danish | [/da/](https://quantumhumanitarian.ink/da/) |
| it | Italian | [/it/](https://quantumhumanitarian.ink/it/) |
| nl | Dutch | [/nl/](https://quantumhumanitarian.ink/nl/) |
| ja | Japanese | [/ja/](https://quantumhumanitarian.ink/ja/) |
| zh | Chinese (Simplified) | [/zh/](https://quantumhumanitarian.ink/zh/) |
| pl | Polish | [/pl/](https://quantumhumanitarian.ink/pl/) |
| fa | Persian/Farsi (RTL) | [/fa/](https://quantumhumanitarian.ink/fa/) |
| ur | Urdu (RTL) | [/ur/](https://quantumhumanitarian.ink/ur/) |

Each language has:
- Native title, meta description, keywords
- Localized OG and Twitter Card tags
- Full JSON-LD schema (Book, Person, WebSite, BreadcrumbList, FAQPage)
- Translated body content across all sections
- Country names localized in the buy-region grid
- Amazon storefront link localized where available (amazon.fr, .de, .es, etc.)

## Tech

- Vanilla HTML / CSS / JS — no framework, no build step
- [Three.js](https://threejs.org/) — quantum particle field in the hero
- [GSAP + ScrollTrigger](https://greensock.com/gsap/) — scroll animations
- Cormorant Garamond + Inter (Google Fonts)
- Hosted on cPanel / LiteSpeed at Namecheap

## Structure

```
.
├── index.html          # English root
├── sitemap.xml         # 15 URLs with hreflang cross-refs
├── robots.txt
├── llms.txt
├── cover.jpg           # Book cover
├── author.jpg          # Author portrait
├── fr/index.html       # French
├── es/index.html       # Spanish
├── de/index.html       # German
├── no/index.html       # Norwegian
├── ar/index.html       # Arabic (dir=rtl)
├── sv/index.html       # Swedish
├── da/index.html       # Danish
├── it/index.html       # Italian
├── nl/index.html       # Dutch
├── ja/index.html       # Japanese
├── zh/index.html       # Chinese Simplified
├── pl/index.html       # Polish
├── fa/index.html       # Persian/Farsi (dir=rtl)
└── ur/index.html       # Urdu (dir=rtl)
```

## How to update

Each language page is a self-contained HTML file with inline CSS and JS. To update:

1. Edit the relevant `<lang>/index.html` directly, or edit the root `index.html` to change English.
2. If you add a new language, also update `sitemap.xml` and add a `<link rel="alternate" hreflang="...">` plus a language-switcher entry to every other language's nav.
3. Zip changed files preserving folder structure (e.g. `index.html`, `fr/index.html`, `sitemap.xml` inside the zip).
4. Upload the zip via cPanel File Manager → /home/youreyws/quantumhumanitarian.ink/ → drop into the upload area.
5. Right-click the zip → Extract.
6. Delete the zip.

## License

All rights reserved. The book *Quantum Humanitarian* and its content are © 2025 Ali Al Mokdad.

## Contact

- Author: [alialmokdadleadership.com](https://alialmokdadleadership.com)
- Book on Amazon: [B0F6LSRKDG (Kindle)](https://www.amazon.com/dp/B0F6LSRKDG)
