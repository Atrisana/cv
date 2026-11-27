# Atri Sana — Portfolio

This is a static portfolio. Keep index.html and atri-sana.jpg together in the site folder. Open index.html in a browser to preview it. It uses no build step, external JavaScript, or remote fonts.

## Publish free with GitHub Pages

1. Sign in to GitHub and create a public repository (for a personal site, name it your-github-username.github.io; otherwise any repository name works).
2. Upload index.html and atri-sana.jpg to the repository root. You may include this README too.
3. For a repository site, open Settings → Pages, choose Deploy from a branch, select main and / (root), then save. A personal site repository may publish automatically after the first push.
4. Wait for GitHub Pages to finish publishing. The URL appears in Settings → Pages. Open it on a phone and desktop.
5. This page is configured for https://atrisana.github.io/addio/. If you publish it at a different address, update the Open Graph URL and canonical link in index.html.

GitHub Pages setup guide: https://docs.github.com/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Publish free with Netlify

1. Sign in to Netlify and choose Add new site → Deploy manually.
2. Drag the outputs folder (containing index.html and atri-sana.jpg) into the deploy area.
3. Netlify provides a public *.netlify.app address. In Site configuration → Change site name, choose an available name.
4. Add that actual site URL as the Open Graph URL and canonical link in index.html if desired, then redeploy after edits.

Netlify deploy guide: https://docs.netlify.com/deploy/create-deploys/

## Before sharing on LinkedIn

- Confirm the dates, role title, project scope, institutional naming, all counts and scores, and market research figures against original documents.
- The reported NEC points are shown as 1,260 / 1,170 because that is what the source HTML says. Confirm the scoring basis and whether the numerator can exceed the stated maximum.
- Check whether the NEC report, RIIMAGINE event, The Startup Files, and VentureHorizon figures or names can be publicly shared.
- Replace any stale contact details and confirm the LinkedIn URL opens the intended profile.
- The WhatsApp contact link uses the number supplied in chat with India’s +91 dialing code. Confirm the number is WhatsApp-enabled and the country code is correct before publishing.
- Add a résumé download or project/report links only if you want them public and can share them.
- The source’s skill chart assigned numeric Focus Index values without describing a measurement method. Those scores were omitted; skills are listed without ratings.

## Content and functionality notes

- The original HTML referred to Tailwind, Chart.js, and Lucide files in a neighboring *_files folder. That folder was not included with the uploaded HTML, so those relative references would fail on a different computer.
- The original source also contained links to a file:///C:/Users/.../Downloads/... path, which are local-only and cannot work for visitors. This version uses in-page links.
- The original HTML embedded some project illustrations as base64 data, while other project cards used generated styling. The only image dependency in this version is the included profile photo.
- Original interactive behavior included project filters/details, skill charts, local-only profile customization, clipboard buttons, and a contact form that only copied a message draft. Project details now use native accessible disclosure controls; the charts and local customization were removed. Contact links open email, WhatsApp, and LinkedIn.
- There is no hosted contact-form backend. The email button opens the visitor’s mail app.
- The page includes mobile-responsive layout, keyboard focus indicators, a skip link, reduced-motion support, SEO description, and social preview title/description.
- The profile portrait is copied from the LinkedIn profile photo visible in your signed-in browser. It is a local static image, so upload atri-sana.jpg with index.html; changing the LinkedIn photo later will not update the site automatically.


