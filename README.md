# Joybait 🐰🌈

Playful one-page website for **$JOYBAIT** — the pump.fun memecoin that uses **100% of creator rewards** to fund bounties for tiny acts of kindness (helping someone old cross the road, complimenting a stranger IRL, and friends).

**CA:** `BDCXV5WKmx2G6g1qGsmSCfc78QNiMzPqUVLKsEaVpump`
**Trade / watch live:** https://pump.fun/coin/BDCXV5WKmx2G6g1qGsmSCfc78QNiMzPqUVLKsEaVpump

## Running it

It's a single static page with zero build steps and zero dependencies:

```bash
# just open it
open index.html

# or serve it
python3 -m http.server 8000
```

Deploys as-is to GitHub Pages, Netlify, Vercel, or any static host.

## Structure

```
index.html              # the whole site (HTML + CSS + JS inline)
assets/joybait-logo.jpg # the happy bunny
```

## Nice touches

- Animated sky: drifting clouds, spinning sun rays, swaying flowers, fluttering butterflies
- Click-to-copy CA with a confetti burst
- Pet the bunny (click the logo) for floating hearts — 7 pets unlocks a secret toast
- Bounty board styled as sticky notes, scroll-reveal sections, joy meters
- Respects `prefers-reduced-motion`

After deploying, consider updating the `og:image` / adding an `og:url` meta tag to the live URL for nicer link previews.
