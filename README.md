# outerrimlabs.app

The Outer Rim Labs studio website. One static file, no build step — `index.html`
is the whole site. Live at [outerrimlabs.app](https://outerrimlabs.app).

## Deploy

Vercel project `outerrimlabs-site` (team `outer-rim-labs`).

```
npx vercel --prod     # run from THIS folder, not from inside .vercel/
```

Or connect this repo in Vercel → Git, and every push to `main` deploys itself.

## Layout

- `index.html` — the site
- `design/logo-options.html` — the twin-sun mark, five variants, and why the
  original (two overlapping discs) was retired: it read as Mastercard

## Editing

- Copy follows the ORL brand voice: short sentences, underdog never bitter,
  Star Wars only as structure and metaphor (fleet, hangar, callsigns) — never
  Lucasfilm names, ships or quotes. Privacy lines belong in headline copy.
- Fleet roster: one `<article class="ship">` per app. Swap "Public name coming."
  for the real name and store badges when a ship launches.
- Hangar log: prepend a `<li>` per month. Plain, concrete, numbers welcome.
- Palette and type are the tokens in `:root`. Don't add colours.

Next.js is the studio's choice for web *apps*; this page has no app logic, so
one file is the simplest thing that works.

*An Outer Rim Labs starfighter. Not affiliated with Lucasfilm or Disney.*
