# Ghungroo Bar & Restaurant website

One-page static site (HTML/CSS/JS, no build step) for Ghungroo Bar & Restaurant, Nacharam, Hyderabad.
Open `index.html` in a browser, or deploy the folder as-is to any static host (Vercel, Netlify, cPanel).

## What's on the page

1. Hero: photo, "Restaurant and bar in Nacharam", Get directions
2. Visit: address, hours (open/closed now is computed in IST), last order, private room
3. Food: signature dishes by group (names only, no prices; the full menu stays offline)
4. Bar: drinks by group, no prices
5. Private room for parties
6. Close and footer: Get directions, address, hours, credits

"Get directions" opens the Google Maps link https://maps.app.goo.gl/PfNpKAbqHh7Kubyq9

## To confirm with the owner

| Item | Value used | Source |
|---|---|---|
| Address | Narmada Arcade, above HDFC Bank, Snehapuri Colony, Nacharam | Cvent listing, matches the Maps pin |
| Hours | Every day, 12:00 to 23:00 (24-hour, so the "Open now" line works) | Cvent listing |
| Last order | 23:00 | Menu booklet ("Last Order 11-00 PM") |
| Private room | Up to 40 guests | Cvent listing |
| Phone, email, socials | Not shown | Not supplied |
| Legal drinking age | 21 | Telangana rule |

## Photographs to replace

All 10 photos are Unsplash stand-ins (all Indian: an Indian bar counter, Indian dishes and guests), not Ghungroo's own. Replace each file in `assets/img/` with a real
photo of the same subject (same file name, WebP or JPG, landscape, window light, no flash):

| File | Where | Shoot |
|---|---|---|
| hero-bar-room.webp | Hero (now 4 brand bottles side by side) | Ghungroo's own bar shelf with the brands you pour |
| dining-room.webp | Visit | The dining room, set tables |
| biryani.webp | Food strip | Keema biryani, top-down |
| fish-curry.webp | Food strip | Chepala pulusu or a curry spread |
| kebabs.webp | Food strip | Tandoori chicken or kalmi kebab |
| curry-naan.webp | Food strip | A curry with roti or naan |
| brand-*.webp | Bar (6 bottle tiles) | Your own bottles of each brand on the bar top |
| guests.webp | Parties | The private room, set for a party (no people) |
| thali.webp | Parties | A shared table spread |

## Design system

Built with the taste-skill kit (`assets/`): place layout, Source Serif 4 + Libre Franklin,
magenta `#b8086a` from the menu booklet on warm off-white. Page CSS is in the `<style>` blocks in `index.html`.

## Logo

In `assets/logo/` (SVG is vector, use it for print and signboards; PNG for WhatsApp, social and documents):

| File | Use |
|---|---|
| ghungroo-logo-cocktail.svg / .png | Main logo: cocktail glass with a ghungroo-bell garnish, name, "Bar & Restaurant", "A legacy of 30 years" |
| ghungroo-logo-cocktail-dark.svg / .png | Same, on dark backgrounds |
| ghungroo-logo-cocktail-magenta.svg / .png | Same, on brand magenta (signboard, social posts) |
| ghungroo-logo-cocktail-horizontal.svg / .png | Wide version for the website header and letterheads |
| ghungroo-icon-cocktail.svg / .png | Round icon: favicon, WhatsApp and Instagram profile picture |
| ghungroo-logo-stacked*.svg, ghungroo-mark.svg | Earlier alternative with three bells on a cord |

Colours: magenta #B8086A, deep magenta #7A0546, brass gold #D2A849, cream #F7F3EC, ink #2A2622.
Fonts: Source Serif 4 (name) and Libre Franklin (small caps line), converted to outlines in the SVGs.
