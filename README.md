# Brian Valencia García — consultancy site

A single-page "living CV" and consultancy landing page. No build step, no framework.
Just `index.html` and an `assets/` folder. Open `index.html` in any browser to preview.

## Deploy in ~5 minutes (pick one)

**GitHub Pages (free, keeps your domain option open)**
1. Create a public repo, e.g. `brianvgarcia.github.io` (or any name).
2. Drag `index.html` and the `assets/` folder into it and commit.
3. Repo -> Settings -> Pages -> Source: `main` branch, root. Save.
4. Live at `https://<username>.github.io/` in a minute or two.

**Netlify (free, drag-and-drop, easiest custom domain)**
1. Go to app.netlify.com -> "Add new site" -> "Deploy manually".
2. Drag the whole `site` folder onto the drop zone. Done.
3. Add a custom domain later under Site settings -> Domain management.

**Custom domain** (e.g. brianvalencia.com): buy it, then point it at either host.
Netlify makes this the least painful.

## What's in this version

- Sober, light-first design. Cool cartographic-paper background, deep slate ink,
  one confident teal accent, and the three domain colours (crop / water / risk)
  used sparingly as a map legend rather than as the whole scaffolding.
- Light / dark toggle in the top nav (sun / moon icon). Default is light; the
  choice is remembered per browser. Falls back gracefully if storage is blocked.
- New logo: a small topographic contour mark (the "hills" of an elevation map).
- Notebooks section featuring six public GitHub gists, including the land-cover
  comparison with guest contributor Fabio Castro-Llanos credited.
- Six publications, including the 2018 Frontiers in Plant Science Espeletia paper.

## Before you go live, optional tidy-ups

- **Google Scholar link.** I used the ID from your profile (`user=9-GvmV0AAAAJ`).
  Open Scholar and confirm the URL still matches.
- **Citation count.** I wrote "200+". Update if Scholar shows a different number.
- **Email.** Currently `jbrayanvalenciag@gmail.com`. If you want a more
  professional address for consulting, swap it everywhere (it appears ~4 times).
- **Headshot.** `assets/brian.jpg` is your existing one. Swap if you have a
  higher-res square crop (800px+).

## Editing

Everything is in `index.html`. Colours are CSS variables at the very top, defined
twice: once under `:root` (light theme) and once under `[data-theme="dark"]`.
Change a value in both places to keep the two themes in sync. Copy is plain HTML,
edit it directly.

Built to a quality floor: responsive to mobile, keyboard focus, reduced-motion
respected. No em-dashes anywhere, per your house style.
