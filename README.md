# كُفُّوا أَلْسِنَتَكُمْ عَنْهُمْ (Kuffo Alsinatakum)

A trilingual (Arabic / English / Turkish) scholarly site that examines historical claims about figures of Islamic history, using isnad analysis and a fixed set of eleven criteria.

**Live site:** https://kuffo-alsinatakum.github.io

## Structure

| Path | Content |
|---|---|
| `/` | Arabic (primary): homepage, `terms/`, `standards/`, `figures/`, `contact/` |
| `/en/`, `/tr/` | English and Turkish versions, same page names as Arabic |
| `images/` | Diagrams and illustrations (WebP) and link-preview images (`og-*.jpg`) |
| `sitemap.xml`, `robots.txt` | Search-engine files; add every new page to `sitemap.xml` |
| `404.html` | "Page not found" page |

Each page is a standalone HTML file with its own CSS; header and navigation are repeated in every file.

## Adding a new page

1. Create it in all three languages with the same file name (e.g. `figures/x.html`, `en/figures/x.html`, `tr/figures/x.html`).
2. Copy the `<head>` block from a sibling page and update the title, `description`, `canonical`, `hreflang` and `og:` URLs.
3. Add the three URLs to `sitemap.xml`.
4. Save images as WebP and give `<img>` tags `width`, `height` and `loading="lazy"`.

## Publishing

Hosted on GitHub Pages from the `main` branch. `project-summary.md` (working notes) and this README are excluded from the published site via `_config.yml`.
