# Connetic Founder Social Studio

A web app for building Brad Zapp / Connetic social posts, with the July 2026
starter batch and all founder photos included.

## IMPORTANT: keep the folder structure

Upload **everything in this folder, with its folders intact** — `index.html`
must sit next to the `assets/` and `uploads/` folders and the two `.js` files.
The app loads its logo, founder photos, and library images from those folders,
so if they're missing, images won't show.

```
index.html        <- the app (open this)
support.js        <- app runtime
seed.js           <- the baked-in July 2026 batch
assets/           <- logo, brand images, founder headshot
uploads/          <- the 35 founder photos
```

## Deploy (GitHub → Vercel)

1. **GitHub**
   - Sign in at github.com → **New repository** → name it `connetic-studio` → **Create**.
   - **Add file → Upload files**, then **drag this whole folder's contents in**
     (index.html, support.js, seed.js, and the assets/ and uploads/ folders).
     GitHub keeps the folders when you drag them.
   - **Commit changes**.

2. **Vercel**
   - vercel.com → **Sign up** → **Continue with GitHub**.
   - **Add New… → Project** → import `connetic-studio` → **Deploy** (defaults).
   - You get a live URL like `connetic-studio.vercel.app`.

## Updating the app

Re-upload the changed file(s) to the same repo and commit. Vercel auto-redeploys.
Saved work in each browser is preserved across updates.

## Where work is saved

Work is stored in **each browser's local storage** (private to that browser).
Use **Export ▾ → Export backup (JSON)** and **Import backup** to move work
between machines. (A shared "everyone sees the same work" cloud database is a
separate add-on that requires connecting a database.)
