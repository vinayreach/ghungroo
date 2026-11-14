# Ghungroo Bar & Restaurant website

One-page static site (HTML/CSS/JS, no build step) for Ghungroo Bar & Restaurant, Nacharam, Hyderabad.
Open `index.html` in a browser, or deploy the folder as-is to any static host (Vercel, Netlify, cPanel).

## What's on the page

Dark lounge design (plum-charcoal, cream, gold, magenta), one self-contained `index.html` (its own CSS, no kit files needed):

1. Hero: full-screen photo of Ghungroo's own back bar, "Nacharam's bar & restaurant for 20 years", live open/closed status
2. Our story: the two hosts, the story text, then the main hall, kitchen team and long table
3. Food: signature dishes by group (no prices) beside four photos
4. Bar: the bar with the Kingfisher fridge, Indian whisky, rum and beer brands
5. Whisky list: every whisky served, plus a bottle collage
6. Visit: the building at night, address, hours, Get directions
7. Footer: logo, address, hours, 21+ line, credits

There is no party room or private room; do not add one. The previous light design is kept in `.review/index-v1-light.html`.

"Get directions" opens the Google Maps link https://maps.app.goo.gl/PfNpKAbqHh7Kubyq9

## To confirm with the owner

| Item | Value used | Source |
|---|---|---|
| Address | Narmada Arcade, above HDFC Bank, Snehapuri Colony, Nacharam | Cvent listing, matches the Maps pin |
| Hours | Every day, 12 noon to 11 PM | Cvent listing |
| Last order | 11 PM | Menu booklet ("Last Order 11-00 PM") |
| Years open | 20 years | Owner |
| Phone, email, socials | Not shown | Not supplied |
| Legal drinking age | 21 | Telangana rule |

## Photographs

**Ghungroo's own** (from `~/Desktop/Claude/ghunghroo-photos`, graded by `.review/grade.py`: the "evening" look for the building, bar and halls, "gold" for the chef):

| File | Where | Source photo |
|---|---|---|
| real-visit-front-night.webp | Visit | #77, building front at night |
| real-hero-bar.webp | Home page banner | #81, lit back bar, wide crop |
| real-bar-side.webp | Bar section | #6, bar with the Kingfisher fridge |
| real-story-team.webp | Story (gold look) | #54, kitchen team |
| real-trio-hall.webp | Story trio | #16, main hall with round sofa |
| real-trio-table.webp | Story trio | #85, long table, second hall |
| real-trio-staff.webp | Story trio | #56, staff in the main hall |
| real-kitchen-chef.webp | Food menu card (header) | #57, chef in the kitchen |

**Still stand-ins:** the four food photos (biryani, curries, tandoori, palak) are Unsplash, because the shoot has no food. The whisky collage and Indian-whisky collage are built from Wikimedia Commons bottle photos (see credits.html).

**Still to shoot:** 4 to 8 dishes (keema biryani, chepala pulusu, kalmi kebab, a curry with naan), top-down or 45°, daylight.

## Design system

All styles are in the `<style>` block of `index.html`: colour tokens on `:root`, Source Serif 4 for headings and Libre Franklin for text. The logo on the dark header is `assets/logo/ghungroo-logo-cocktail-horizontal-on-dark.svg`.

## Logo

In `assets/logo/` (SVG is vector, use it for print and signboards; PNG for WhatsApp, social and documents):

| File | Use |
|---|---|
| ghungroo-logo-cocktail.svg / .png | Main logo: cocktail glass with a ghungroo-bell garnish, name, "Bar & Restaurant", "A legacy of 20 years" |
| ghungroo-logo-cocktail-dark.svg / .png | Same, on dark backgrounds |
| ghungroo-logo-cocktail-magenta.svg / .png | Same, on brand magenta (signboard, social posts) |
| ghungroo-logo-cocktail-horizontal.svg / .png | Wide version for the website header and letterheads |
| ghungroo-icon-cocktail.svg / .png | Round icon: favicon, WhatsApp and Instagram profile picture |
| ghungroo-logo-stacked*.svg, ghungroo-mark.svg | Earlier alternative with three bells on a cord |

Colours: magenta #B8086A, deep magenta #7A0546, brass gold #D2A849, cream #F7F3EC, ink #2A2622.
Fonts: Source Serif 4 (name) and Libre Franklin (small caps line), converted to outlines in the SVGs.
