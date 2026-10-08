# Chuma Mbambisa Legacy Foundation

This repository contains the static website for the Chuma Mbambisa Legacy Foundation. The current build is designed for a nonprofit landing page and general information flow without online donation processing enabled yet.

## Goal

The site is intentionally structured so it can go live now for content and brand visibility, while future donation and payment integration can be added without rebuilding the entire site.

## Structure

- `index.html` — main landing page
- `about.html` — organization overview
- `contact.html` — contact form and contact details
- `friends-of-chuma-golf.html` — event page
- `assets/` — shared CSS/JS libraries
- `css/` — custom site styles
- `js/` — front-end scripts
- `image/` — brand and gallery images
- `php/` — email/mailer integration area for future use

## Important note on donations

Online donation functionality is intentionally not enabled in this branch because the payment details and processing setup are still pending. The website is prepared for future integration, but the public-facing pages are ready to go live without breaking the site.

## Local preview

From the project root, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## GitHub Pages preview

Use the repository Settings > Pages option and publish the `production-ready` branch from the root.

Expected preview URL pattern:

```text
https://jono420dante-art.github.io/chuma-mbambisa-foundation/
```

## Future updates

When changing the site in future:

1. Keep the static pages and shared assets structure intact.
2. Use the `production-ready` branch as the working branch.
3. Avoid hardcoding donation or payment details before they are confirmed.
4. Add any new backend functionality behind a clear placeholder or `coming soon` message until live payment details are final.
5. Keep the contact and general information pages updated before publishing.

## License

This repository is for the foundation website and is maintained for the project team.
