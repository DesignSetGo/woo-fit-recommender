<!-- AUTO-GENERATED from packages/astro/src/packs/woo/components/FitRecommender. Edit there, then run: npm --prefix packages/astro run gen -->

# Size & Fit Recommender

Three-question fit quiz that recommends a size and remembers the answer so future product pages are one tap.

## Manifest

```json
{
  "manifest_version": 1,
  "id": "woo-fit-recommender",
  "name": "Size & Fit Recommender",
  "description": "Three-question fit quiz that recommends a size and remembers the answer so future product pages are one tap.",
  "version": "0.1.0",
  "entry": "index.html",
  "isolation": "iframe",
  "display": {
    "modes": [
      "block",
      "page"
    ],
    "default": "block"
  },
  "permissions": {
    "read": [
      "commerce"
    ],
    "write": []
  },
  "commerce": {
    "providers": [
      "woocommerce"
    ],
    "endpoints": [
      "products"
    ]
  },
  "runtime": {
    "sandbox": "strict",
    "external_origins": []
  },
  "bundleDefaults": {}
}
```

## Install

Upload this bundle as a zip via `wp-admin → DesignSetGo Apps → Add app`, or deploy with the CLI:

```bash
designsetgo apps deploy --path examples/woo-fit-recommender/
```

## Source

Generated from `packages/astro/src/packs/<pack>/components/<Component>/`. To edit, change the source and re-run `npm --prefix packages/astro run gen`.
