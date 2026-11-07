# Bigelow Ventures LLC

Static public company directory at https://bigelowventuresllc.com.

## Deployment

Netlify automatically publishes `dist/` from this repository's `main` branch. No build step, backend, database, or environment variables are required. `netlify.toml` retains the existing publish directory and response headers.

## Local preview

Run `python3 -m http.server 8765 --directory dist` and open http://localhost:8765.

## Website previews

The five JPEGs in `dist/assets/` are actual public homepage snapshots captured November 7, 2026 via the thum.io screenshot service and compressed for local hosting. They are illustrative previews; the linked business websites contain current information. To refresh one, capture the public homepage at 1440px wide, replace the corresponding JPEG, and retain its filename. The page does not request images from a screenshot service at runtime.

The circle motif and favicon are lightweight inline/vector artwork. The page uses system fonts, native links, reduced-motion support, and a single-column phone layout.
