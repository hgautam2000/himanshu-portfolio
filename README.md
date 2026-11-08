# Himanshu Gautam — Portfolio Site

Static HTML/CSS site with no build step. Every page is a complete HTML document, so the folder can be hosted as-is (GitHub Pages, Netlify, Vercel, or any static host).

## Pages
- `index.html` — Home
- `theater.html` — Stage credits, anchored by Desi SNL (content from desisnl.com)
- `films.html` — Short films (Bindi is live; other cards are placeholders)
- `modeling.html` — Lookbook grid and comp-card stats (placeholders)
- `podcast.html` — Yappy Yaar episodes (placeholders; currently unlinked from the site while it's being planned)
- `about.html` — Bio, photos, contact

## Design
- `style.css` holds everything shared. Colors are CSS variables at the top: red (`--crimson-*`) is the lead accent, gold is secondary. Dark mode is built in.
- Fonts: Bebas Neue (headlines), Work Sans (body), Space Mono (labels), all from Google Fonts.
- The nav bar is repeated in every page, so a new page means adding a link in every page's nav.

## Still to fill in
Anything in `[square brackets]` is a placeholder: theater training, Bindi role/director/year, other films, demo reel, modeling photos and stats, podcast episodes and links, bio paragraph, email and Instagram.

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.
