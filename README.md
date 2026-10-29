# Zephyr Antiques

One-page website for Zephyr Antiques, 270 W Main St, Abingdon, Virginia.

Plain HTML and CSS with no build step:

- `index.html` holds all three tabs (The Shop, About Abingdon, Our Location)
- `styles.css` holds the styles. After changing it, bump the `?v=` number on its link in `index.html` and `404.html` so browsers fetch the new version.
- `img/` holds photos (WebP, sized for how they display), logos and the walkthrough video
- `404.html`, `robots.txt` and `sitemap.xml` are for GitHub Pages and search engines. The business details Google reads (address, hours, phone) are in a JSON block in the `<head>` of `index.html`; update them there too if they change.

Live at https://zephyrantiquesabingdon.com, served by GitHub Pages from `main`. Pushing to `main` updates the site.

## Preview locally

```bash
python3 -m http.server 4391
```

Then open http://localhost:4391.
