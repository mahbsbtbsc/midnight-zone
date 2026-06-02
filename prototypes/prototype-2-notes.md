# Prototype 2 — p5.js + GBIF API

Rebuilt entirely in p5.js instance mode.
Connected to live GBIF Occurrence API (api.gbif.org).
GBIF occurrence counts now drive creature size scaling.

## What worked
- Real API data feeding the visual
- p5.js rendering pipeline
- GBIF status bar showing live load progress

## What needed changing
- Creatures still circles — no distinct silhouettes
- GBIF showing 0 due to sandbox CORS restrictions
- Empty space below the last creature
