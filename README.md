# Colorful Astro Portfolio

A responsive, colorful, multi-page portfolio starter built with Astro.

## Included pages
- `/` — Home
- `/about/` — About
- `/services/` — Services
- `/contact/` — Contact

## Upload the ready-made static website to cPanel
1. Open the `dist` folder in this project.
2. Upload **the contents of `dist`** (not the `dist` folder itself) to `public_html`.
3. Make sure `index.html` is directly inside `public_html`.
4. Visit your domain.

No Astro, Node.js, PHP, or database is needed on the production hosting account.

## Edit the Astro source
You need Node.js (LTS) on your computer:
```bash
npm install
npm run dev
```
Edit the files under `src/`, then build:
```bash
npm run build
```
Astro recreates the `dist/` folder. Upload its contents to your hosting again.

## Before publishing
- Replace “Your Name” and the sample biography with your details.
- Replace the sample email address and social links.
- Update the service descriptions and project examples.
- The contact form currently opens the visitor's email application using `mailto:`. For a hosted form submission, connect a form service or your own backend.
- Replace the remote Unsplash image URLs with your own optimized images if desired.

## URL and hosting notes
The site uses standard directory-style URLs such as `/about/`. The included `.htaccess` helps Apache/cPanel serve directory index files and enable compression/browser caching where supported. If your host does not allow `.htaccess`, remove it; the pages still work.
