# AVERO Productions — website

Static site, no build step. Two pages:

- `index.html` — Home: intro, contact links, Services, Working with us
- `contact.html` — Contact + About us

Contact: `representative@averoproductions.com` · Instagram `@averoproductions`

## Run it locally

```bash
cd ~/avero-site && python3 -m http.server 8080
```

Then open http://localhost:8080.

## Design

Dark résumé layout: black background, white text, grey secondary text, 1px hairlines.

- Header: flower logo + "AVERO Productions," / subtitle on the left, nav on the right.
- Body: left sidebar (intro paragraph + hairline contact list) and right content column of sections. Each section is a bold label followed by rows; each row is title + grey meta on the left, bullet points on the right.
- Links get a ↗ arrow. Hover turns orange (`#FF751F`, the logo colour) — the only accent on the site.
- Type: Inter 400 / 600, 17px body.
- Logos: `assets/logo/avero-white.svg` (used on this dark site), `avero-black.svg` for light backgrounds.

## Update the details

Search both pages for `representative@averoproductions.com`, `averoproductions` and `Miami, FL`.
