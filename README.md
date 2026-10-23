# LVC Digital – ebook store site

Static website for LVC DIGITAL LTD (England & Wales, company no. 16628298). Plain HTML and CSS, no build step.

## Pages
- `index.html` – home, ebook catalogue, how it works, FAQ
- `terms.html`, `privacy.html`, `refunds.html`, `contact.html` – required legal and support pages

## Before going live
1. In `index.html`, replace the three placeholder ebooks (title, description, price) with real products.
2. Each `Buy now` button links to a Stripe Payment Link (see `index.html`).
3. In `contact.html`, replace `support@example.com` with the real support email.

## Preview locally
Open `index.html` in a browser, or run `python -m http.server` in this folder.

## Deploy
GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
