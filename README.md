# Vyra — premium local-first wellness tracker

A responsive, single-file fitness and wellbeing web application built in vanilla HTML, CSS and JavaScript.

## Run
Open `index.html` in Chrome, Safari, Firefox or Edge. No build step or dependencies are required. (Google Fonts are optional and require internet access.)

## Features
- Private local profile onboarding and customizable daily goals
- Dashboard with calorie, protein, exercise and hydration status
- Food diary with vegetarian-focused lookup list, portion scaling, custom macros, calorie and macro targets, and food suggestions
- Workout diary with editable exercise-burn estimates
- Daily mood, sleep, stress and journal check-ins
- Body measurements: weight, waist, chest and biceps
- Interactive hover/tap charts, 7/30/90/365-day or since-beginning range
- JSON export/import backups, date picker, entry deletion, responsive navigation

## Deploy to GitHub Pages
1. Create a **public** GitHub repository for the site (e.g. `vyra-tracker`).
2. Upload `index.html` to the root of the repository.
3. Go to **Settings → Pages → Build and deployment → Deploy from a branch**. Select `main` and `/ (root)` and save.
4. GitHub will display your public site URL in the Pages settings.

**Important:** GitHub Pages provides web hosting, **not user accounts, a synced database, or secure storage**. This version stores data using `localStorage` in each browser. You can use it privately for a year, but export a JSON backup regularly. Anyone accessing a deployed URL can use their own independent browser data. Do not use this as a secure account-based service for the public yet.

## Before public launch with true accounts
Add a backend service (e.g. Supabase/Firebase), proper email/password or social authentication, user-scoped database authorization, verified nutrition database, data deletion/export flow, privacy policy, and server-side security rules. Nutrition estimates and workout burn values are illustrative. This version is a prototype and not medical advice.
