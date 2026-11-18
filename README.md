# megarisk.com landing page

Static landing page for [megarisk.com](https://megarisk.com).

## Contents

- `index.html`: the full page, with the animated logo hero and "How we work", "The model" and contact sections. Styles, script, logo SVG and favicon are inline.
- `og-image.png`: the 1200x630 link preview image used by Open Graph and Twitter/X cards.
- `apple-touch-icon.png`: 180x180 icon for iOS home screens and the structured data logo.
- `robots.txt` and `sitemap.xml`: crawler basics. Update `lastmod` in the sitemap when the page content changes.
- `social/`: HTML sources for the two PNGs above. To regenerate, open each file at its stated size (1200x630 or 180x180) and take a screenshot, for example with Playwright.
- `fonts/`: self-hosted variable fonts, the same families the draft site uses. Rethink Sans for headings and Instrument Sans for body text. Both are licensed under the SIL Open Font License (license files included).

## Local preview

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

Upload `index.html`, the `fonts/` folder, the PNGs, `robots.txt` and `sitemap.xml` to any static host. There is no build step and there are no dependencies.

## Notes

- The logo animation runs once on load, and sections fade in on scroll. Visitors with reduced motion enabled see everything without animation.
- The contact email appears in two places in `index.html`: the "Get in touch" button and the footer.
