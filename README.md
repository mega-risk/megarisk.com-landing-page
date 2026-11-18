# megarisk.com landing page

Static landing page for [megarisk.com](https://megarisk.com).

## Contents

- `index.html`: the full page. Styles, script, logo SVG and favicon are inline. Fonts load from Google Fonts (Rethink Sans, Instrument Sans).

## Local preview

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

Upload `index.html` to any static host. There is no build step and there are no dependencies.

## Notes

- The logo animation runs once on load. Visitors with reduced motion enabled see the static logo.
- The contact email appears in two places in `index.html`: the "Contact us" button and the footer.
