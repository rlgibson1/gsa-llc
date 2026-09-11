# Product images

Hosted here so eBay can fetch them by HTTPS URL when a listing is created
(`https://rlgibson1.github.io/gsa-llc/images/<VCPN>/<file>`).

Rules:

- One folder per Keystone VCPN (`images/C2CGI148BLK/01.jpg`, `02.jpg`, ...). JPEG or PNG,
  at least 500 px on the longest side (1000 px or more preferred), under 12 MB each.
- `manifest.json` lists every folder with its `source` and `license`. No entry, no listing:
  the sync tool refuses a manifest entry without both. Never competitor photos or scraped
  marketplace images; brand data pools (DCi, ASAP, SEMA Data), brand dealer portals, or a
  written permission kept at sales@ are the only sources.
- `placeholder/` is a generated test image used to prove the listing pipeline. It is never
  published on a listing.
