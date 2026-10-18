# Eco Activity Box

Lao-first, English-switchable, buildless HTML/CSS/JavaScript activity library for Loop2Life.

Public path: https://matsuokakoki.github.io/looptolife/eco-activities/

## Features

- Eight illustrated activities and ten supplied TikTok posts (nine video posts and one photo post).
- Official TikTok iframe player; connected only when the visitor presses Load. Original short links and creator attribution are always available.
- Ecobrick materials and four steps adapted from the existing Loop2Life project page. Other activities use explicitly labelled general preparation and workshop checklists, not unverified tutorial transcripts.
- Browser-local language preference, checklist progress, completion stamps, and reduced-motion support.
- Keyboard-accessible native dialog, keyboard tabs, category filters, responsive layout, deep links such as `#activity-ecobrick`.
- QR SVG pointing to the public path and bilingual A4 print layout at `print.html`.

## Maintenance

Update `activities` in `app.js` to change post IDs, authors, original short links, titles, or descriptions. Update both language dictionaries together. Illustrations in `assets/crafts.svg` and `assets/workshop.svg` are conceptual artwork, not screenshots or claims about the exact tutorial results.

Before workshop use, have a Lao speaker review the translations and a facilitator review all tutorials, exact materials, and age suitability. Video contents were not visually verified during implementation; no exact duration, cost or difficulty is asserted. Do not have children melt or burn plastic. Ecobrick furniture construction needs separate expert supervision.

TikTok availability depends on the original post, browser, network, and region. The site does not proxy, download or rehost the tutorials. It has no backend and adds no analytics. Language and progress stay in the visitor's browser when localStorage is available. Clearing browser data clears progress. The app remains usable when storage is unavailable, but cannot persist progress.

## Deployment

No npm dependencies or build step. Keep this folder at repository root and serve the repository through the existing GitHub Pages setup. All asset links are relative to support the `/looptolife/` project path. The original project styling and language script remain separate.

The QR SVG encodes the exact public path above, with a four-module quiet zone and medium error correction. Print it at a readable size with its white border intact.
