# Elektrihind24 – Vercel versioon

Puhastatud ja moderniseeritud versioon Elektrihind24 lehest, mis on valmis Vercelisse üles panemiseks.

## Mis on muudetud / paranenud

- Eemaldatud kogu Bloggeri spetsiifiline kood
- Puhtam, moodsam tume disain
- Sticky header + backdrop blur
- Parem mobiilivaade ja spacing
- Säilitatud kogu funktsionaalsus (hinnad, graafik, kalkulaator, ilm, KKK jne)
- Valmis staatilise saidina Vercelisse

## Kuidas Vercelisse üles panna

### Variant 1 – kõige lihtsam (drag & drop)

1. Mine aadressile [vercel.com](https://vercel.com) ja logi sisse (GitHub / Google / e-post)
2. Kliki **Add New… → Project**
3. Vali **Upload** või **Import**
4. Lohista kogu `elektrihind24` kaust üles (või ainult `index.html`)
5. Deploy

### Variant 2 – GitHubi kaudu (soovitatav)

1. Loo uus GitHub repository
2. Laadi sinna üles `index.html` (ja soovi korral `vercel.json` + `README.md`)
3. Vercel.com → **New Project** → vali see repository
4. Deploy

### Variant 3 – Vercel CLI

```bash
npm i -g vercel
cd elektrihind24
vercel
```

## Märkused

- Andmed tulevad endiselt Google Apps Scriptist + Eleringi varulahendusest.
- Kui Apps Scripti URL peaks kunagi katki minema, töötab leht ikkagi Eleringi API kaudu.
- Ilmaandmed tulevad Open-Meteo API-st (tasuta, ilma võtmeta).

## Kohalik testimine

Lihtsalt ava `index.html` brauseris või käivita kohalik server:

```bash
npx serve .
```
