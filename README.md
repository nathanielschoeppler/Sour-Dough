# Bonny's Sourdough

Order website for Bonny's Sourdough (bread + cookies, pickup in Caledonia, MI).

Customers pick items, enter name, phone and pickup date, and the order is texted to Bonny.

## Editing
Open `index.html` and look for `EDIT HERE` near the bottom:
- `bonnyPhone` – Bonny's cell number (orders get texted here).
- `bonnyEmail` – optional, adds an "Email it" button.
- `formspreeEndpoint` – optional. Create a free form at formspree.io and paste its URL here; orders are then emailed to Bonny automatically.
- `MENU` – names, descriptions and prices.

## Going live (free)
GitHub repo → Settings → Pages → Source: "Deploy from a branch" → pick the branch, folder `/ (root)` → Save.
