Steps to build manually:
- `npm i`
- Add favicon in `index.html`: `<link rel="icon" type="image/png" href="assets/Logo-square-transparent.png" />`
- Replace all `figma:asset` URLs with relative paths
- `npm run build`
- `cd dist`
- `npx serve`
- Copy outer HTML and paste to a new file
- Copy `assets` directory
- Commit and push

Steps already implemented at original:
- Change page title to "AdAisle" in `index.html`
- Insert Calendly link `https://calendly.com/yannis-drosidis-cal-adaisle/30min`
- Replace logo with transparent image
- Change logo to `<img className="h-6 sm:h-9">` to make it smaller on mobile
- Change the hero section that has the CTA buttons to `<div className="flex flex-col sm:flex-row items-center gap-4">` to make them stack on mobile