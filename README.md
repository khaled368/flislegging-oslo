# FLISLEGGING OSLO · Priskalkulator

Static calculator website with a saved price catalogue for fliser, hjørnelister, materialer and labor.

- **Live website:** https://elegant-paprenjak-1f6eba.netlify.app/
- **Languages:** Arabic / Norsk
- **Currency:** NOK
- **Entry point:** `index.html` (complete self-contained page; includes styles, scripts and logo)
- **Hosting:** Netlify, publish directory `.`, no build command (`netlify.toml`)

## Deployment

Connect this GitHub repository (`main`) to the **existing** Netlify site `elegant-paprenjak-1f6eba`. Once linked, each push to `main` deploys automatically to the same domain.

**Important:** Saved items/prices use browser-local storage and stay with the same site origin and browser profile. Before major changes, export a backup from the calculator. Do not create a second Netlify site if you want to keep locally stored data on the same domain.
