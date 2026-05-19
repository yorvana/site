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
{% assign beta_form_url = "https://docs.google.com/forms/d/e/PLACEHOLDER/viewform?embedded=true" %}
```

Replace that value with the real Google Forms embed URL. The fallback direct link is derived from the same value.

## Screenshots

Add production screenshots to `assets/screenshots/` using this naming convention:

- `01-vehicle-list.png`
- `02-record-detail.png`
- `03-add-service-record.png`
- `04-settings.png`

The landing page currently reserves fixed phone-ratio placeholder slots so screenshots can be dropped in later without changing the layout.
