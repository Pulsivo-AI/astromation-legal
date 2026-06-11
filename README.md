# AstroMation — Legal & Support Site

Static legal and support pages for **AstroMation**, the astrology app by
[Machinity](mailto:info@machinity.ai) that calculates birth charts entirely
on-device and offers AI-written readings.

## Pages

| Page | Purpose |
| --- | --- |
| [`index.html`](index.html) | Landing hub linking to all documents |
| [`privacy.html`](privacy.html) | Privacy Policy (on-device data, AI interpretations, subscriptions) |
| [`terms.html`](terms.html) | Terms of Use (auto-renewable subscriptions, EULA, liability) |
| [`support.html`](support.html) | Support page with FAQ and contact |

These URLs are referenced from the App Store / Google Play listings, so page
filenames and the substance of the legal text should stay stable.

## Design

Pure static HTML + a single shared stylesheet (`styles.css`) — no build step,
no JavaScript.

- Celestial dark theme with a layered starfield and nebula gradients
- Fraunces (display) + Outfit (body) via Google Fonts
- Sticky navigation, table of contents with anchor links on legal documents,
  accordion FAQ on the support page
- `prefers-reduced-motion` respected; print stylesheet renders the legal
  documents as clean black-on-white

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Contact

Machinity — [info@machinity.ai](mailto:info@machinity.ai)
