# CleverTap Geofencing Gallery — Field Guide 08

An interactive, self-contained gallery of 120 location-based geofencing campaign examples for CleverTap, spanning 15 industries. Each example pairs a real-world scenario with the channel it runs on, a device mockup of the customer-facing message, the SDK event payload, and a copy-paste setup sheet.

Live: https://shijunneo-bot.github.io/ct-geofencing-gallery/

## What's in this repo

- `index.html` — the entire gallery. Single self-contained file: all CSS, JS, and images are inline, no external assets or CDN calls.
- `llms.txt` — plain-text summary at the site root for AI engines and LLM crawlers (AEO).
- `og-image.png` — 1200x630 social share card (Open Graph + Twitter).
- `README.md` — this file.

## Deploy (GitHub Pages)

1. Create a public repo named `ct-geofencing-gallery` under the `shijunneo-bot` account.
2. Upload `index.html`, `llms.txt`, and `og-image.png` to the repo root.
3. Settings > Pages > Build and deployment > Deploy from a branch > `main` > `/ (root)` > Save.
4. Live in about a minute at the URL above.

Note: `llms.txt` and `og-image.png` must sit at the repo root for AEO and social previews to resolve.

## The Field Guide Family

1. AMP Email Templates — https://shijunneo-bot.github.io/amp-email-gallery/
2. Rich Push Examples — https://shijunneo-bot.github.io/rich-push-gallery/
3. SMS Examples — https://shijunneo-bot.github.io/ct-sms-field-guide/
4. WhatsApp Examples — https://shijunneo-bot.github.io/whatsapp-addon-gallery/
5. Linked Content — https://shijunneo-bot.github.io/ct-linked-content-gallery/
6. Recommendations and Catalogs — https://shijunneo-bot.github.io/ct-recommendations-gallery/
7. Reminders — https://shijunneo-bot.github.io/ct-reminders-gallery/
8. Promos — https://shijunneo-bot.github.io/ct-promos-gallery/
9. Custom HTML In-App — https://shijunneo-bot.github.io/ct-template-gallery/
10. Geofencing (this guide) — https://shijunneo-bot.github.io/ct-geofencing-gallery/

## Notes

Mechanics are verified against docs.clevertap.com and developer.clevertap.com. Sample coordinates, brand names, and figures in the mockups are illustrative, not real campaign data.
