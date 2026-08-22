# Your Portfolio Site

A dark, gallery-style portfolio for graphic design + UI/UX work, with a real
admin panel (no code needed) for editing text and adding images to either
category.

## What's inside
- `index.html` — the site itself
- `content/site.json` — your name, tagline, about text, contact info
- `content/work.json` — your project entries (title, category, image, etc.)
- `images/uploads/` — where uploaded images live
- `admin/` — the admin panel (Decap CMS), free and open source

## Deploy it for free (10 minutes)

1. **Create a GitHub account** (if you don't have one) at github.com — done, this repo already exists.

2. **Sign up at netlify.com** (free) and choose "Import an existing project."
   Connect your GitHub account and pick this repo (`designer-portfolio`).
   Leave build settings blank (no build command needed) and deploy.
   You'll get a free URL like `yourname.netlify.app`.

3. **Turn on the admin login.** In your Netlify site dashboard:
   - Go to **Site configuration → Identity** → Enable Identity.
   - Under Identity settings, set registration to **Invite only**.
   - Go to **Identity → Services** and enable **Git Gateway**.
   - Go to the **Identity** tab and click **Invite users** — invite your own
     email address, then accept the invite email.

4. **Log in to your admin panel** at `yourname.netlify.app/admin`. From there
   you can edit your name/about/contact info, and add, edit, or delete work
   items — including uploading images — without touching any code. Changes
   save straight to your GitHub repo and the live site updates automatically.

5. **Optional — custom domain.** In Netlify, go to **Domain management** to
   connect a domain you own, or keep the free `.netlify.app` address.

## Notes
- The two work categories (UI/UX Design, Graphic Design) are set in
  `admin/config.yml` — add more by adding to the `options` list there.
- Sample entries and placeholder images are included so the page isn't empty
  on first load — delete or replace them from the admin panel.
