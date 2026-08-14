# praporscic.github.io

Root GitHub Pages site for this account. It serves two things at the domain root:

- `index.html` — a simple developer landing page listing the apps published under this account.
- `app-ads.txt` — required so Google can verify AdMob ownership for every app under this account
  (`pub-4519849723410518`) that sets its App Store Connect **Marketing URL** to
  `https://praporscic.github.io`.

Google's app-ads.txt crawler reads only the hostname from the Marketing URL field — it always
checks `https://<hostname>/app-ads.txt` at the root, ignoring any subpath. A per-app GitHub Pages
project page (e.g. `praporscic.github.io/CandleApp/`) can't host this file itself; it has to live
here, at the account root. That's also why the Marketing URL can safely point at this landing page
(or any path on this host) instead of directly at the txt file — only the hostname matters.

Apps currently relying on this file:
- Candle Blow: Birthday Wish (`ca-app-pub-4519849723410518~3794951913`)
- Silence - White Noise for Sleep (`ca-app-pub-4519849723410518~3569611274`)
