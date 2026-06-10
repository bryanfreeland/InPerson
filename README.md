# InPerson

A neighborhood-scale marketplace for hands-on classes — pottery, knife skills, welding,
snowboarding, watercolor, and more — taught by real people in their own kitchens, garages,
studios, and mountains.

Built from a Claude Design handoff as a single self-contained static page (React 18 +
in-browser Babel via CDN, no build step). Deploys to any static host.

## Surfaces

- **Browse** — hero search, category filters, class-card grid, instructor editorial section.
- **Class detail** — image mosaic, instructor, key facts, schedule picker, reviews, sticky booking card.
- **Booking** — 4-step modal (review → who's coming → payment → confirmation).

## Run locally

It's a static file — open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Deploy

Static; no build command, no output directory. On Vercel, import the repo and deploy —
the included `vercel.json` enables clean URLs.
