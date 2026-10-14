# Nightreign Sorceries

I kept arguing with myself about which sorcery to pick up as my main spell in Elden Ring Nightreign, so I wrote my opinion down as a tier list and put it online. The rankings are mine, based on my own runs, and they only change when I change my mind.

Live at **https://sorceries.jor.dev/**

## Features

1. Every sorcery in the game sorted into four tiers: Use This, Pretty Good, If You Have To and Don't Use.
2. Most spells carry a one line note on why they landed where they did, like damage, range, speed or whether the spell is pierce or aoe. Most tier 4 spells have no note, I just do not use them.
3. The tier colors are mine, the rest of the look follows the jor.dev brand: Montserrat, light and dark mode following your system setting, and the tier labels are readable by their number and name, not by color alone.
4. The list is a plain array in the page script, so changing a ranking is editing one line.

## Run locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Files

```
index.html            the page, with the styles and the spell list inline
brand/                jor.dev tokens, base styles, fonts and logo, copied by brand/scripts/install.sh
favicon.svg           from brand/logo/icon.svg
favicon.ico           32x32 favicon
apple-touch-icon.png  180x180 app icon
og-image.png          1200x630 social preview, made with brand/scripts/og-image.sh
robots.txt            crawler policy with the sitemap URL
sitemap.xml           sitemap
CNAME                 sorceries.jor.dev
CLAUDE.md             rules for working on this repository
LICENSE               the Unlicense
```

## Any issues?

This is a hobby project I have spent quite some hours on. If you have any issues, feel free to open a GitHub issue or contact me. Otherwise, this code is unlicensed, so do whatever you want with it: https://unlicense.org/

## Buy me a coffee

Don't. If you let me know you used or enjoyed this, you have already made the best donation.
