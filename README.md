# Roundabout Lifestyle Logistics — website

A single-page static site. No build step: `index.html` is the whole site.

## Launch on GitHub Pages

1. Create a new repository on GitHub (for example `roundabout-site`). It must be **public** on a free GitHub plan.
2. Upload `index.html`, `.nojekyll` and this README to the root of the repository (Add file → Upload files → Commit).
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Use your own domain (optional)

1. In **Settings → Pages → Custom domain**, enter your domain (e.g. `www.roundaboutmd.com`) and save. GitHub adds a `CNAME` file to the repo.
2. At your domain registrar, add a `CNAME` record pointing `www` to `<your-username>.github.io`.
3. Once DNS resolves, tick **Enforce HTTPS**.

## Fill in before launch

Search `index.html` for these placeholders and replace them:

| Placeholder | Replace with |
|---|---|
| `[PHONE NUMBER]` | Business phone line |
| `[BOOKING LINK]` | Your Calendly / Acuity booking page URL |
| `[PRIVACY POLICY LINK]` | Privacy policy page |
| `[FAQ LINK]` | FAQ page |

Brand colors: forest green `#1E5B45`, marigold `#F2B33D`. To change them, find-and-replace those hex codes in `index.html`.
