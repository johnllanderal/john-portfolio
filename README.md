# John Andre: Customer Support & E-commerce Virtual Assistant Portfolio

A one-page portfolio site built with plain HTML, CSS, and JavaScript. No build step and no dependencies,
so it deploys directly on GitHub Pages.

## Files
- `index.html`  all page content, SEO metadata, and the case-study text (inside `<template>` blocks)
- `styles.css`  all styling (colors and fonts are CSS variables at the top)
- `script.js`   mobile menu, case-study panel, work-sample tabs, tool filter, and the pre-filled contact message
- `assets/john-profile.jpg`  profile photo (location metadata removed)
- `assets/favicon.svg`  browser tab icon
- `assets/samples/order-followup-tracker-demo.csv`  downloadable demonstration tracker (fictional data)

## Deploy (GitHub Pages)
1. In the repo, delete the old `index.html`, `styles.css`, and `script.js`, then upload the new ones.
2. Upload the `assets` folder with everything inside it. It must keep the name `assets`, and the `samples` folder must stay inside it.
3. Settings > Pages: Deploy from a branch > `main` > `/ (root)`.
4. Wait about a minute, then open the site in a private window to avoid cached files.

## Editing content
- Stat cards under the hero: the `.proof` list in `index.html` (plain text).
- Services: the `<details class="service">` blocks.
- Case studies: the `<template id="case-...">` blocks near the bottom of `index.html`.
- Work samples: the `<div class="tabpanel">` blocks. Keep the "Demonstration sample" label on anything that is not real client work.
- Contact details: search for `john.llanderal21@gmail.com` and `639214512028` (in `index.html` and `script.js`).
- Booking: the Calendly URL appears in the `#book` section of `index.html`.
