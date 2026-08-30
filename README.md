# anirudhkumar.com

Personal site for Anirudh Kumar. Static HTML/CSS/JS, no build step, no framework, no CMS.

Built on the Daylight personal brand system (Cove Teal `#066489`, Fraunces + Inter type pairing).

## Structure

- `index.html`, `about.html`, `work.html`, `writing.html`, `community.html`, `contact.html` &mdash; pages
- `css/style.css` &mdash; the entire design system as CSS custom properties and components
- `js/main.js` &mdash; mobile nav toggle only
- `assets/` &mdash; favicon and images

## Local preview

Open `index.html` directly in a browser, or serve the folder with any static server, e.g.:

```bash
npx serve .
```

## Deploy

Static files only. Point any static host (Hostinger static hosting, Netlify, Vercel, GitHub Pages, Cloudflare Pages) at this repo root.
