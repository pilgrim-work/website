# Instructions for Claude

This is Hans's personal website, pilgrim.work: an Astro static site deployed to GitHub Pages by `.github/workflows/deploy.yml` on every push to `main`.

Hans has no programming experience. Keep the setup simple and explain changes in plain Swedish.

- Site content is in English. Pages are markdown files in `src/pages/` using `layout: ../layouts/Base.astro` (adjust `../` for depth).
- Navigation lives in `src/layouts/Base.astro`; styling in `src/styles/global.css`.
- Don't add frameworks, CMSes, or dependencies unless Hans asks. A plain markdown page is the default for new content.
- Don't change `public/CNAME` or the deploy workflow without explaining why.
- Run `npm run build` before pushing to make sure the site builds.
- Hans owns the content and wording. Don't rewrite his texts beyond what he asks for.
