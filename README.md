# Sonam Info Solutions website

Static luxury 3D showroom (HTML + CSS + Three.js from CDN). No build step.

## Deploy on Vercel
1. Create a new GitHub repository and upload every file in this folder (keep the `assets` folder).
2. On vercel.com choose **Add New > Project**, import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Click **Deploy**.

## Edit content
Open `index.html`.
- Products and prices: the `const D=[...]` list in the script. Format: `[name, price, oldPrice (0 if none), category, imageKey]`.
- Photos: `assets/img/` and the `const IMG={...}` list.
- Phone numbers, address and hours: search for `919793014315` and `Naza Market`.

Note: the three Customer Reviews are marked SAMPLE until real reviews are added.
