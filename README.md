# SNSAI Commerce System

Full-stack ecommerce web system built with Next.js, TypeScript, and a local JSON datastore.

## What is included

- Animated landing page with layered motion and role-based entry points
- Unified authentication for user, seller, and admin roles
- User storefront with product detail, cart, wishlist, orders, and dashboard
- Seller console with product creation, order visibility, demand signals, and performance stats
- Admin control tower with seller approval, product moderation, order review, and flagged-user insight
- `SNSAI` recommendation/search layer:
  - Natural-language query interpretation
  - Real-time search suggestions
  - Behavior-aware product ranking
  - Image-palette product matching
  - Explainable recommendation reasons

## Demo credentials

- Admin: `admin` / `admin123`
- Seller: `seller` / `seller123`
- User: `riya` / `user123`

## Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Master run launcher

The project now includes a one-command launcher that:

- installs missing dependencies
- retries failed installs once after cleaning npm cache
- runs automatic lint fixes
- rebuilds the production app
- clears stale build output if needed
- picks a free port if `3000` is already occupied
- starts the whole system

Use either of these:

```bash
./run-system.command
```

or

```bash
npm run master:run
```

Extra modes:

```bash
npm run master:prepare
npm run master:test
```

## Important notes

- Seeded data is stored in `data/db.json`.
- If you want a fresh reset, delete `data/db.json` and restart the app.
- New seller registrations are created in pending mode until approved by the admin.

## Developer & Note
- Satya Narayan Sahu
- This entire software is not for personal or commerical use and not open for developers to download it, modify or use it at any kind. This software is entirely registered and IPR for Satya Narayan Sahu only.
