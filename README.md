# Stephen Cotterrell

A lightweight personal website built with semantic HTML and CSS, hosted on GitHub Pages.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8000> in a browser. No package installation or build step is required.

## Files

- `index.html`: introduction, background, and current direction
- `about.html`: short biography
- `styles.css`: shared typography, responsive layout, and accessible focus styles
- `images/` and `photos/`: original site assets
- `CNAME`: existing custom domain, `stephencotterrell.com`

The site has no JavaScript, external font requests, or runtime dependencies. Icons are inline SVGs. Existing page URLs and the custom domain are retained.

## Before publishing

Check both pages at desktop and mobile widths. Confirm that local navigation, image paths, the skip link, and the GitHub destination work. Review the introduction and biography before making changes public.

This refresh does not change GitHub Pages settings. Publishing requires applying the reviewed changes to the branch used by the existing Pages configuration.
