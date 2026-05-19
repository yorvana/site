# yorvana/site

Public website for [Yorvana](https://yorvana.app) — a privacy-first Android app for keeping a personal log of vehicle maintenance.

Served via GitHub Pages at `yorvana.app`.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## Landing page structure

The launch page is `index.html` and uses custom Jekyll layouts/includes instead of a packaged theme. Styling lives in `assets/css/site.css`; do not add a CSS framework, JavaScript framework, Google Fonts, analytics, or tracking pixels.

The privacy policy remains at `/privacy-policy/`. Keep the policy text unchanged unless the app privacy policy itself is being updated.

## Closed beta form

The embedded Google Form URL is defined once near the top of `index.html`:

```liquid
<!-- BETA_FORM_EMBED_URL -->
{% assign beta_form_url = "https://docs.google.com/forms/d/e/1FAIpQLScSCJReVMRNzUf1-YISM8oSdjYv524J_hwZv4Tg1HhKuhkDQg/viewform?embedded=true" %}
```

Replace that value if the Google Form changes. The fallback direct link is derived from the same value.

## Screenshots

Production screenshots live in `assets/screenshots/` and are referenced directly from `index.html`:

- `vehicle-list.png`
- `vehicle-list-dark.png`
- `vehicle-history.png`
- `vehicle-history-dark.png`
- `vehicle-history-hero.png`
- `vehicle-history-hero-dark.png`
- `add-service-record.png`
- `add-service-record-dark.png`
- `record-detail-attachment.png`
- `record-detail-attachment-dark.png`

Gallery replacements should stay at phone screenshot proportions so the landing page grid remains stable. Hero screenshots are cropped from the service history screen and should keep the current `672x1493` dimensions.
