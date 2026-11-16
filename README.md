# pilgrim.work

Hans webbplats för Navigate by Conviction. Byggd med [Astro](https://astro.build) och publicerad med GitHub Pages.

## Hur det fungerar

- Varje sida är en textfil (markdown) i `src/pages/`. Filens plats blir adressen:
  - `src/pages/philosophy.md` → pilgrim.work/philosophy/
  - `src/pages/tools/bearings.md` → pilgrim.work/tools/bearings/
- När en ändring sparas i `main` bygger GitHub sajten och publicerar den automatiskt. Det tar några minuter.
- Bilder och nedladdningsbara filer läggs i `public/`. `public/bearings.pdf` blir pilgrim.work/bearings.pdf.

## Lägga till en sida

Kopiera en befintlig fil, byt namn och ändra `title` överst. Lägg in en länk till den från en annan sida.

## Ändra utseendet

- Färger och typsnitt: `src/styles/global.css`
- Meny, sidhuvud och sidfot: `src/layouts/Base.astro`

## Rör inte

- `public/CNAME` (kopplar domänen)
- `.github/workflows/deploy.yml` (publiceringen)
