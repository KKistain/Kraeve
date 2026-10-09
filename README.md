# Kraeve

Kraeve is a responsive, single-page marketing website for a South African
digital marketing agency. It is a static site built with HTML, CSS, and
JavaScript; there is no build step or package installation.

## Files

- `index.html` — the complete website.
- `hero.jpg` — the hero section background image.

## Preview locally

Open `index.html` in a browser, or serve the folder locally:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

In the repository settings, open **Pages**, select **Deploy from a branch**,
choose the `main` branch and the `/(root)` folder, then save. GitHub Pages will
publish the site from `index.html`.

The site loads its web fonts from Google Fonts; system font fallbacks are
included.
