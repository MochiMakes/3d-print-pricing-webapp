# 3D Print Pricing Calculator (Web App)

Client‑side React app for 3D‑print pricing. Includes:
- Cost Builder (per‑run → per‑unit)
- Order Calculator (Etsy, Shopify, eBay, Mercari fee presets)
- Target‑profit price solver
- Platform comparison
- Mobile‑friendly, dark‑mode, localStorage persistence

## Local dev
```bash
npm i
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Deploy to Vercel
1. Push this folder to a GitHub repo.
2. On Vercel → **New Project** → import your repo.
3. Framework preset: **Vite** (defaults are fine).
4. Build Command: `npm run build`
5. Output Directory: `dist`
6. Click **Deploy**.

> Tailwind is already configured. No backend required.

## Notes
- All numbers are editable; presets reflect common fees. Confirm your exact account rates.
- Data saves locally in your browser (localStorage).


## PWA (Installable app)
- Already configured: `public/manifest.json`, icons, and `public/sw.js`.
- After deploy, open the site in Chrome → **Install app** (desktop) or **Add to Home Screen** (mobile).
