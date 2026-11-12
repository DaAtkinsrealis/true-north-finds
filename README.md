# True North Finds

Online store at https://truenorthfinds.com/ (Vercel project `true-north-finds`).

Static front-end: `index.html` (storefront) + `admin.html` (admin page).
Data lives outside this repo: Supabase project for products/orders/auth,
jsonbin.io for configuration. Product images are hosted on Unsplash.

Deploy: push to `main` — Vercel auto-deploys.

Note: `alipay-qr.jpg` / `wechat-qr.jpg` are referenced by `index.html`
(`PAYMENT_QR`) but were never uploaded to the deployment (404 on the live
site), so the checkout QR display has no image source yet.
