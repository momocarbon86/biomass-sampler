# Biomass Field Sampler: documentation, tutorial and demo site

A static website: no build step and no server code. It has:

| Page | File |
|---|---|
| Home (with promo video) | `index.html` |
| Tutorial with screenshots | `tutorial.html` |
| Documentation (method, formulas, exports, references) | `docs.html` |
| Live demo of both apps, with made-up data | `demo.html` → `demo/app/`, `demo/lite/` |

## Publish on GitHub Pages
1. Create a repository on github.com, for example `biomass-field-sampler`.
2. Upload **the contents of this folder**, including the hidden `.nojekyll` file, to the repository root: **Add file → Upload files**, drag everything in, then **Commit**.
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
4. After about a minute, the site is at `https://<your-username>.github.io/biomass-field-sampler/`.

To update the site, upload the changed files again; Pages redeploys automatically.

## Before you publish
- Contact emails on the site: morrischanda86@gmail.com and momocarbon86@gmail.com.
- **The repository and the site are public on a free GitHub account**, and the demo folders contain the working app code. Anyone can copy it. If you're selling the app, consider a private repository (GitHub Pages from a private repository needs a paid plan), or keep only the documentation public.
- The demo uses separate storage from the real app, so it never mixes with real field data. The demo data is made up.

© 2026. All rights reserved.
