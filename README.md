# ELVTD GEAR — elvtdgear.com

Premium athletic wear. Built For More.

Single-page brand site (pure HTML/CSS/JS, no build step).

## Hosting (GitHub Pages)
1. Repo Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / root → Save
2. Site goes live at https://jneato-art.github.io/elvtdgear/

## Connecting elvtdgear.com
1. In Settings → Pages → Custom domain, enter `elvtdgear.com`
2. At the domain registrar, add DNS records:
   - `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` record for `www` → `jneato-art.github.io`
3. Enable "Enforce HTTPS" once DNS propagates

## Swapping in real photos
Replace the image URLs in `index.html` with files dropped into `assets/` (e.g. `assets/hero.jpg`).

## Email capture
The Notify form is front-end only. Hook it to Mailchimp, Klaviyo, or formspree.io when ready (see comment in `index.html`).
