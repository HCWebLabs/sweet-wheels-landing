# Sweet Wheels — Sweet Deals! (Mock Landing Page)

A pastel, mobile-first landing page demo for a fictional dessert truck.  
Built to show how playful, themed landing pages can drive a single action:
**find today’s route** and **spin a promo wheel**.

> **Heads-up (disclaimer)**  
> This is a **portfolio mock**. “Sweet Wheels” is **not a real business**.  
> The map uses sample coordinates and the spinner is for **demonstration only**—no real prizes or data collection.

## Preview
- Live (GitHub Pages): `https://YOUR_USERNAME.github.io/YOUR_REPO/`
- One-file demo: `index.html` (no build step)

## Features
- 🎯 Landing-page focus: one screen, two CTAs (Maps + Spin to Win)
- 🍨 Ultra-pastel theme with **Pacifico** headline
- 🗺️ Free, no-key map via **Leaflet + OpenStreetMap**
- 🎡 Canvas spinner (accurate pointer math, smooth easing)
- 📱 Mobile-first, a11y-minded (skip link, focus styles, ARIA)
- 🖼️ “Sweet Shots” image grid with **Show more** on small screens

## Tech
- HTML, CSS, vanilla JS
- Fonts: Pacifico, Inter, Poppins (Google Fonts)
- Icons: Font Awesome (CDN) — or swap in your own SVG sprite
- Map: Leaflet + OpenStreetMap tiles (free)

## Getting Started
Just open `index.html` in a browser. Everything comes from trusted CDNs.

## Deploy to GitHub Pages
1. Create a new repo (public).  
2. Add `index.html`, `README.md`, and (optional) `assets/` folder.  
3. (Optional) add an empty file named **`.nojekyll`** in the repo root.  
4. Push to `main`.  
5. In **Settings → Pages**:  
   - *Source*: **Deploy from a branch**  
   - *Branch*: **main** / **root**  
   GitHub will give you the site URL in a minute or two.

**Custom domain?** Add your domain in Pages, then commit a `CNAME` file with just the domain.

## Customize
- Colors and spacing: edit CSS variables in `<style>` (`:root{…}`).
- Spinner prizes: edit the `slices` array in the “Spinner logic” script.
- Map center: change `LIVE_LOCATION` in the script block.
- Social icons: replace FA `<i>` tags with your own inline SVG sprite if you prefer.

## Disclaimer (friendly)
This site is a **fictional mock** for portfolio/educational purposes.  
No products are for sale, no orders are taken, and no personal data is collected.
Any likeness to real businesses is coincidental. Map pins and prizes are pretend.

## Credits
- Map tiles © OpenStreetMap contributors (rendered via Leaflet)  
- Fonts: Google Fonts — Pacifico, Inter, Poppins  
- Icons: Font Awesome Free  
- Placeholder images: placehold.co

## License
Code © YOUR NAME. You may reuse this template in your own portfolio with attribution.
Third-party libraries remain under their respective licenses.
