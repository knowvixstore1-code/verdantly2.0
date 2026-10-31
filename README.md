# Verdantly — Gardening Store Starter

A responsive gardening storefront inspired by the general shopping structure of the supplied Ugaoo page archive, with original branding, copy, colors and layout.

## Run locally

- Easiest: open `index.html` in a modern browser.
- For PWA/service-worker behavior, serve this folder over HTTP (for example `python -m http.server 8000`) and open `http://localhost:8000`.

## Included

- Responsive home page, category shortcuts, product cards, product search, category filter and sorting
- Shopping bag with quantity controls, remove item, subtotal and demo delivery calculation (saved to localStorage)
- Demo sign-in form and browser-local account state
- Demo checkout flow and order confirmation; no real payment is collected
- Admin demo with local inventory quantities and demo order count
- Newsletter demo (browser-local only)
- Web app manifest, custom icon assets and a basic service worker

## Important before publishing

This is a **front-end starter**, not a production commerce backend. Authentication, inventory, customer data, newsletter signups, and orders are stored in the visitor's browser and are not secure or shared across devices. The admin panel is not protected. Payment UI is a placeholder and does not process money. Before launch, connect a backend/database, server-side auth and role permissions, real order management, shipping/tax logic, transactional email, and a payment gateway such as Razorpay/Stripe with server-side verification. Do not use the demo admin panel for real customer or order data.

## Brand

**Verdantly** is a suggested working name and should be checked for domain, trademark and social-handle availability before commercial use.

## Reference assets

A selection of plant/gardening images was extracted from the provided saved-page asset archive to support this local prototype. The page does not include Ugaoo logos or claim affiliation with Ugaoo. Confirm you have rights to each image before commercial deployment; replace any reference images with your own licensed product photography.
