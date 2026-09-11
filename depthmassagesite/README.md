# Depth Massage

Single-page site for Depth Massage — in-suite and in-home massage therapy in the greater Twin Cities (St. Louis Park, MN). Plain HTML/CSS/JS, no build step.

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying to GitHub Pages

1. Go to the repo's **Settings → Pages**.
2. Under "Build and deployment", set **Source** to "Deploy from a branch".
3. Choose the `main` branch and `/ (root)` folder, then save.
4. GitHub will publish the site at `https://<username>.github.io/Depth_Website/`.

No build step is required — the site is served as-is.

## Swapping in real assets

Placeholder images live in `assets/images/`:

- `logo.svg` — replace with the real logo/wordmark (SVG or PNG; update the `<img>` reference in `index.html` if you change the file extension).
- `headshot.svg` — replace with the real photo (e.g. `headshot.jpg`), then update the `src` in the About section of `index.html`.

Review quotes, address, phone number, Instagram handle, and the Square booking link are all in `index.html` and can be edited directly — no build tooling involved.
