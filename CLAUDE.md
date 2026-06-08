# peidiwu-website

Personal website for Peidi Wu (founder of Spotter AI). Static HTML/CSS, no build step.

## Local dev

Requires a local server (CSS uses absolute paths, so `file://` won't work):

```
python -m http.server 8080
```

Then open http://localhost:8080.

## Deploy

Push to `main` — GitHub Pages deploys automatically from the `main` branch. No PR needed.

```
git add <files>
git commit -m "..."
git push origin main
```

## Site structure

- `index.html` — homepage
- `how-i-finally-hit-2000-on-lichess-.../index.html` — chess article
- `a-better-wilks-formula/index.html` — powerlifting article
- `bio/index.html` — redirects to homepage
- `style.css` — shared stylesheet

## SEO status

Meta descriptions, canonical URLs, and Open Graph tags added to all pages (June 2025). Still to do: Google Search Console, sitemap.xml.
