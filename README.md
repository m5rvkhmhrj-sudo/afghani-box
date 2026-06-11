# Afghani Box Website

Single-page static site. No build step, no dependencies. Open `index.html` in a browser or host the folder on any static host (GitHub Pages, Netlify, Vercel).

## What's inside

- `index.html` — full site, CSS and JS embedded
- `images/` — photos and logo pulled from the business's own Instagram (@afghanibox)

## Data sources

Every fact on the site came from the business's own pages:

- Name, tagline ("Foodie Paradise"), concept, brand colors: their logo and Instagram bio
- Address (1220 W Ogden Ave, Unit C, Naperville, IL 60563) and phone (630) 276-3511: their own HFSAA certification post and storefront sign
- HFSAA Halal certification details: their own certification post
- Menu item names (Chicken Kabob Box, Qabuli Palow Box, Chapli Kabob Box, Mantu Box, Lamb Tikka, Lamb Chop Box, the Afghani Box): their Instagram + their DoorDash listing
- Two verified prices (Bolani with Dogh $13.95, Afghan Style Ice Cream $4.99): stated directly in their own Instagram posts
- Photos: their Instagram posts
- Hours (Tue–Sun 12–9, closed Monday): Google Business Profile

Dish descriptions describe what each Afghan dish authentically is plus what is visible in their photos (rice with carrots and raisins, salad, naan, white sauce, chutney). Nothing about their specific recipes was invented.

## IMPORTANT — verify with the owner before selling

1. **Prices.** The Toast online-ordering menu sits behind a Cloudflare bot wall that could not be read automatically, so main-dish prices are NOT printed on the site. The menu lists the dishes and links to the live Toast page for current pricing. Two prices ($13.95, $4.99) are shown because the owner posted them publicly. To print full prices, get them from the owner or from the live Toast menu and drop them into the menu section.
2. **Hours.** Tue–Sun 12:00pm–9:00pm, closed Monday comes from the Google Business Profile, not the restaurant's own posts. Confirm with the owner.
3. **Address unit.** Listed as Unit C based on the Google listing; the HFSAA post shows "1220 W Ogden Ave" without a unit. Confirm.

## Note on photos

Most of the business's Instagram posts are videos; the images used here are the highest-resolution frames available (640–720px wide). They are a bit soft on large screens. If the owner can provide high-resolution food photos, swap them into `images/` using the same filenames for a sharper result. All photos belong to the business.

## How to update

Edit `index.html`. The menu is plain HTML in the `#menu` section — add prices or items directly. Replace any image by dropping a new file into `images/` with the same name.
