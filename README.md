# Appirio Shark Tank — judge scoresheet (hosted copy)

The judging form for the async review round, served from GitHub Pages so judges never
load `script.google.com` — Google rewrites those URLs to an account-scoped
`/macros/u/N/s/...` path when a browser has more than one Google account signed in, and
that path 404s for anyone who isn't the script's owner.

Judges need no Google account. A shared password is the only gate.

**This repo is public and deliberately contains nothing sensitive.** `index.html` is the
form shell: no startup names, no pitch video links, no password. The roster is returned by
the Apps Script endpoint only after the password checks out.

Generated — do not edit `index.html` here. The source is `Index.html` in the private
`appirio-shark-tank-scoresheet` repo; `publish_pages.py` copies it over.
