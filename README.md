# renelobo.com

Personal academic website of René Lobo, built with [Hugo](https://gohugo.io) and the
[HugoBlox](https://hugoblox.com) Academic CV template, and deployed to GitHub Pages.

## Editing content

| What | Where |
| --- | --- |
| Name, bio, links, education, experience, interests | `data/authors/me.yaml` |
| Profile photo | `assets/media/authors/me.png` |
| Homepage sections | `content/en/_index.md` (English), `content/es/_index.md` (Spanish) |
| Publications (one folder each) | `content/en/publications/<slug>/index.md` |
| Projects (one folder each, with `featured.jpg`) | `content/en/projects/<slug>/index.md` |
| Teaching | `content/en/teaching.md` |
| Blog posts | `content/en/blog/<slug>/index.md` |
| Site settings (analytics, theme, footer) | `config/_default/params.yaml` |
| Menu | `config/_default/menus.yaml` |

## Languages

The site is bilingual: English at `/` and Spanish at `/es/`.

- English pages live in `content/en/`, Spanish pages in `content/es/` with the same file names.
- Publications and talks are shared: the Spanish site reuses `content/en/publications/` and `content/en/events/` (see `config/_default/module.yaml`).
- Spanish profile text (bio, experience, awards…) is in `data/es/authors/me.yaml`; anything not set there falls back to `data/authors/me.yaml`.
- Spanish menu and description are in `config/_default/languages.yaml`.

## Running locally

Requires Hugo **extended 0.161.1** (the version pinned in `hugoblox.yaml`), Go and Node.js.

    npm install
    hugo server

Then open <http://localhost:1313>.

Note: Hugo 0.162.0 currently fails to build the HugoBlox `blox` module
(`assignment to entry in nil map` in `build_links.html`), so keep 0.161.1 until upstream fixes it.

## Deployment

Every push to `master` builds the site and publishes it to GitHub Pages
(`.github/workflows/deploy.yml`). One-time setup:

1. In the repository, go to **Settings → Pages** and set **Source** to **GitHub Actions**.
2. In the same page, set **Custom domain** to `renelobo.com` and enable **Enforce HTTPS**.
3. At your domain registrar, point the DNS to GitHub Pages:
   - `A` records for `renelobo.com`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www`: `renelobo.github.io`
