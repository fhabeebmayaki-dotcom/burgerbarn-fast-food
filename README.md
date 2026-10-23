# BurgerBarn — Classic Fast-Food Restaurant Website

A bright, conversion-focused one-page website for a fast-food restaurant: big hero, filterable menu, chefs, special offers, testimonials, hours/location, and a working order cart. Pure static HTML/CSS/JS — the same content structure as a WordPress restaurant build, with zero hosting cost and instant load times.

## What's inside

- **Hero** — full-width burger photography, headline, and dual CTAs (Order Now / View Menu) plus a rating strip.
- **Filterable menu** — 10 items across 4 category tabs (Burgers, Chicken, Sides, Shakes) that filter with a click, every item with photo, description, price, and Add button.
- **Working order cart** — slide-in drawer, quantity +/− controls, live total, demo checkout with confirmation.
- **Special offers** — 3 deal cards (meal deal, family bundle, shake happy hour).
- **Meet the chefs** — 3 team cards with real photos and roles.
- **Testimonials** — 3 customer reviews with avatars and star ratings.
- **Visit us** — opening hours, address, phone, email.
- Fully responsive, vanilla JS, single `index.html` — no build step.

## How a buyer customises it

1. **Name & branding** — replace `BurgerBarn` throughout `index.html`; change colours via the CSS variables (`--red`, `--green`, `--ink`) at the top of the `<style>` block.
2. **Menu & prices** — each item is an HTML card with a `data-category` attribute; edit text/prices directly, or add a card and it joins the tabs and cart automatically.
3. **Offers** — edit the 3 deal cards in the `#offers` section.
4. **Photos** — swap any file in `images/` keeping the same filename (menu items, chefs, hero).
5. **Hours / address** — edit the Visit section and footer.
6. **Checkout** — the cart checkout is a demo confirmation; connect the `checkoutBtn` handler to your payment or ordering provider (e.g. Square, Toast, or a WhatsApp order link) for live orders.

## Files

- `index.html` — the entire site (styles + scripts embedded)
- `images/` — all photography (Unsplash)
- `README.md` — this file

Open `index.html` in any browser, or drop the folder on Netlify / Vercel / GitHub Pages to go live.
