# blockpower-vote

Redirects every URL on blockpower.vote and www.blockpower.vote to the same path on https://blockpower.org (site source: BlockPowerNow/blockpower-site). GitHub Pages cannot send HTTP 301s, so `index.html` and `404.html` redirect with an instant meta refresh plus `location.replace`, keeping the path, query, and hash.

DNS (Namecheap): apex A records 185.199.108.153 / .109 / .110 / .111, `www` CNAME `blockpowernow.github.io`. Mail on @blockpower.vote uses Namecheap email forwarding (MX eforward1-5); leave those records alone.

Replaced the HubSpot CMS hosting (portal 8868419) on 2026-10-01.
