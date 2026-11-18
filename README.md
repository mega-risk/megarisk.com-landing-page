# megarisk.com landing page

Static landing page for [megarisk.com](https://megarisk.com).

## Contents

- `index.html`: the full page. Styles, script, logo SVG and favicon are inline.
- `fonts/`: self-hosted variable fonts, the same families the draft site uses. The page uses Instrument Sans. Rethink Sans, the draft site's headline font, is included for future headings. Both are licensed under the SIL Open Font License (license files included).

## Local preview

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

Upload `index.html` and the `fonts/` folder to any static host. There is no build step and there are no dependencies.

## Notes

- The logo animation runs once on load. Visitors with reduced motion enabled see the static logo.
- The contact email appears in two places in `index.html`: the "Contact us" button and the footer.
