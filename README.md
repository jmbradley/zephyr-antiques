# Zephyr Antiques

One-page website for Zephyr Antiques, 270 W Main St, Abingdon, Virginia.

Plain HTML and CSS with no build step:

- `index.html` holds all three tabs (The Shop, About Abingdon, Our Location)
- `styles.css` holds the styles. After changing it, bump the `?v=` number on its link in `index.html` so browsers fetch the new version.
- `img/` holds photos, logos and the walkthrough video

## Preview locally

```bash
python3 -m http.server 4391
```

Then open http://localhost:4391.
