# NextUpApv

Server rules (APV) for the NextUp Roleplay FiveM server, published as a single static page in Dutch.

Live: https://wall3rsyt.github.io/NextUpApv/

## Contents

Nine chapters: introduction and principles, sanction categories, cheats and exploits, roleplay rules, vehicles, weapons, general rules, staff matters and final provisions.

## Features

- Sidebar navigation that tracks the section in view.
- Collapsible menu on screens up to 992 px wide.
- Light and dark mode toggle.

## Structure

Everything lives in `index.html`: markup, CSS and JavaScript. There is no build step. External resources are Google Fonts (Inter, Rajdhani) and Font Awesome 6.0.0-beta3 from cdnjs.

## Deployment

GitHub Pages serves the root of the `main` branch. A push to `main` updates the live site. The `Jekyll site CI` workflow only test-builds the site; it does not deploy.
