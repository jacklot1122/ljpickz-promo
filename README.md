# LJ Pickz — Promo Page (static site)

Mobile-first signup/promo page. Pure static HTML — no build step needed.

## Deploy to Vercel via GitHub

1. Go to github.com → **New repository** (e.g. `ljpickz-promo`) → create
2. **Upload files**: drag `index.html` and the `assets` folder into the repo → commit
3. Go to vercel.com → **Add New → Project** → import the repo
4. Framework preset: **Other**. No build command, no output directory — just **Deploy**
5. Done. Add your domain under Project → Settings → Domains (e.g. `join.ljpickz.com`)

## Notes

- Checkout buttons use your live Stripe payment links (7-day free trial).
- To change prices/links later, edit `index.html` — search for `buy.stripe.com`.
