# hvt-ledger-home

Home-screen launcher for the **hvt ledger** dashboard (`hvt-ledger-dashboard`, Apps Script web app, access: only the owner).
Apps Script pages are served from Google's domain, so iOS ignores any icon set inside the app; this static page carries
the icon (`apple-touch-icon.png`) and forwards to the dashboard. It contains no data and no secrets — the dashboard URL
only works for the signed-in owner.

- Add to iPhone: open `https://hovthanh93.github.io/hvt-ledger-home/` in Safari, tap **Stay here** within 1.5 s, then Share → Add to Home Screen. Launching the icon forwards to the dashboard after 1.5 s.
- Icons come from `hovthanh93/hvt-ledger` → `assets/icons/` (variant A).
- Hosting: GitHub Pages, branch `main`, folder `/`.
