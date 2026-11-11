# Miracle Education Consultancy Website

English-language company website for **Miracle Education Consultancy Sdn Bhd**.

The redesign follows the `design-taste-frontend` skill and uses its included static design system, UI components, motion layer and browser checks. The public site is a single-page experience with section anchors.

## Preview

Open `index.html` directly, or serve the folder with any static server:

```powershell
npx --yes serve -l 8080 .
```

Then visit `http://localhost:8080`.

## Included public files

- `index.html` — complete homepage
- `miracle.css` — Miracle-specific layout and capability workspace
- `favicon.svg` — brand favicon
- `share.jpg` — social sharing image
- `homepage-preview.png` and `mobile-preview.jpg` — final visual previews
- `programs.html`, `solutions.html`, `about.html`, `contact.html` — redirects for links created during the earlier multi-page draft

## Contact form

The form opens the visitor's email application using the stand-in address `hello@miracle.example`. Nothing is sent automatically and no success message is shown.

Before launch:

1. Replace `hello@miracle.example` in `index.html` with the company's real form endpoint or email address.
2. Add the production domain as `<link rel="canonical">`.
3. Review the programme formats, service claims and commercial terms.
4. Add Privacy and Terms pages that match the company's data-handling practices.
5. Replace any remaining developer copy if the company wants a different primary call to action.

## Verification

- tasteskill copy lint: 0 FAIL, 0 WARN
- consistency checks: 0 FAIL across 1440, 1024, 820, 768 and 390px
- final finish gate: `GATE: PASS`
- performance: 0 FAIL; one desktop font-related layout-shift warning remains

The site has no framework dependency. It can be deployed to Cloudflare Pages, Netlify, Vercel, GitHub Pages or shared cPanel hosting.
