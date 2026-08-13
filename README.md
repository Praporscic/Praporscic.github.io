# praporscic.github.io

Root GitHub Pages site for this account. Its only job right now is serving `app-ads.txt` at the
domain root, so Google can verify AdMob ownership for every app published under this account
(`pub-4519849723410518`) that sets its App Store Connect **Marketing URL** to
`https://praporscic.github.io`.

Google's app-ads.txt crawler reads only the hostname from the Marketing URL field — it always
checks `https://<hostname>/app-ads.txt` at the root, ignoring any subpath. A per-app GitHub Pages
project page (e.g. `praporscic.github.io/CandleApp/`) can't host this file itself; it has to live
here, at the account root.

Apps currently relying on this file:
- Candle Blow: Birthday Wish (`ca-app-pub-4519849723410518~3794951913`)
- Silence - White Noise for Sleep (`ca-app-pub-4519849723410518~3569611274`)
