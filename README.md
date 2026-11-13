# Vyra — Turquoise Fitness Tracker

A single-page, local-first fitness, nutrition, exercise and wellness tracker. Upload `index.html` at the root of your GitHub Pages repository. No build step required.

## Features
- Turquoise/sea-glass theme, dashboard, daily goals, exercise, hydration, mood, body measurements, progress charts and saved local profile.
- No unsourced built-in nutrition facts. Search packaged foods by name or barcode via **Open Food Facts** (internet required), or enter numbers from a manufacturer's label yourself. Community database records **are not verified**; check against the actual label. Generic Indian home-cooked dishes are not automatically measured or verified.
- Save an individual food and reuse it; create saved meals from your saved food ingredients. Nutrients scale by weight.
- Daily rituals: default nimbu pani and curry leaves, plus custom items. Ritual checkboxes deliberately do not add estimated calories.
- Goal reached celebration/confetti for 5 seconds and warning when a tracked goal is exceeded.
- JSON export/import backup and storage in the current browser only.

## Publish to GitHub Pages
1. Extract ZIP. Upload `index.html` and `README.md` (NOT the ZIP itself) into the root of your GitHub repository.
2. In repo Settings → Pages, choose Deploy from a branch → `main` → `/ (root)` → Save.
3. Revisit the Pages URL after deployment.

## Important limitations
- **Not yet a secure public account service.** GitHub Pages does not provide authentication, database or sync between devices. This local prototype cannot recover cleared browser data without a downloaded JSON backup.
- Open Food Facts results are community-contributed and may not be exact; confirm values against your product's nutrition label. Manually entered values have no independent validation. Cooking methods, oils and weights change recipe values. This app cannot guarantee accurate calories or nutrition for arbitrary foods.
- Exercise calories are estimates, not clinical measurements.
- For real public launch, add authentication, row-level access controls, cloud storage, privacy controls, and an authoritative/licensed verified nutrition dataset.
