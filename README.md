# UPSC Prelims PYQ Practice — Website V1

Static website using the supplied UPSC CSE Prelims PYQ dataset. No backend is required for V1; practice progress is stored in browser local storage.

## Included
- Daily/hero PYQ
- Full practice interface with instant feedback and explanations
- All / Mistakes / Bookmarks modes
- Year, subject and text search filters
- Bookmarks and local progress
- Static year and subject browse pages for search-engine-friendly discovery
- Privacy policy page
- Extension promotion section, ready for final Chrome/Edge links after store approval

## Local testing
Run a local static server, for example:

`python -m http.server 8000`

Then open `http://localhost:8000/`.

## Publish
This folder can be deployed to GitHub Pages, Cloudflare Pages, Netlify, Vercel or another static host. Before publishing, replace `YOUR-DOMAIN.example` in `robots.txt` and `sitemap.xml` with the real public domain.

## Ads
V1 intentionally contains no ad-network code. Add monetization only after the site has been reviewed for useful content, privacy disclosures and the chosen ad network's policies.
