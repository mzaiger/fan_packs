# Fan Pack Tracker

A single-page tracker for which pro/college sports teams send free fan
merchandise ("fan packs") by mail — covering **MLB, NFL, NBA, NHL, and
NCAA**.

## What it does

- Lists teams known to mail out free fan gear, each with a confidence tier
  based on how well-documented the offer is
- Includes verified receipt evidence and source URLs for each entry so
  claims can be checked rather than taken on faith
- Sortable tables per league, dark theme UI

## Structure

Everything lives in a single `index.html` — no build step, no
dependencies. Open it directly in a browser or serve it with any static
file host (e.g. GitHub Pages).

## Running locally

```bash
python -m http.server
```

Then visit `http://localhost:8000`.
