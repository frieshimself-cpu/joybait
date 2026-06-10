# Joybait 🐰🌈

Playful one-page website for **$JOYBAIT** — the pump.fun memecoin that uses **100% of creator rewards** to fund bounties for tiny acts of kindness (helping someone old cross the road, complimenting a stranger IRL, and friends).

**CA:** `C6h2WjXEFZrfmGUYDVQJHcdsyXrwYoX3uWdNxsGRpump`
**Trade / watch live:** https://pump.fun/coin/C6h2WjXEFZrfmGUYDVQJHcdsyXrwYoX3uWdNxsGRpump

## Deploy on Vercel (takes ~2 minutes)

1. Go to **[vercel.com/new](https://vercel.com/new)** and sign in (the "Continue with GitHub" option is easiest).
2. Under **Import Git Repository**, find `frieshimself-cpu/joybait` and click **Import**.
   - If it's not listed, click "Adjust GitHub App Permissions" and grant Vercel access to the repo.
3. Touch nothing on the configure screen — no framework, no build command, no env vars needed. Just click **Deploy**.
4. ~30 seconds later you get a live URL like `joybait.vercel.app`. Every future push to the repo auto-deploys.

`vercel.json` is already included (clean URLs, long-cache for the logo, basic security headers).

## Running it locally

It's a single static page with zero build steps and zero dependencies:

```bash
# just open it
open index.html

# or serve it
python3 -m http.server 8000
```

Also deploys as-is to GitHub Pages, Netlify, or any static host.

## Structure

```
index.html              # the whole site (HTML + CSS + JS inline)
assets/joybait-logo.jpg # the happy bunny
vercel.json             # Vercel config (no build step — pure static)
```

## Nice touches

- Animated sky: drifting clouds, spinning sun rays, swaying flowers, fluttering butterflies
- Click-to-copy CA with a confetti burst
- Pet the bunny (click the logo) for floating hearts — 7 pets unlocks a secret toast
- Bounty board styled as sticky notes, scroll-reveal sections, joy meters
- Respects `prefers-reduced-motion`

After deploying, consider updating the `og:image` / adding an `og:url` meta tag to the live URL for nicer link previews.
