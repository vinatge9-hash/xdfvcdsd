# Niyantri — Premium Coffee (Static Demo)

This project is a small static website demo for "Niyantri" — a premium and sleek coffee shop. It includes the following pages:

- index.html — Home / hero and featured items
- menu.html — Full menu with Add to Cart functionality
- cart.html — Cart view with quantity controls and a mock PayPay checkout
- contact.html — Contact form and store information

Key features
- Premium/sleek theme using CSS variables and Tailwind CSS
- Animated buttons and cards (hover & micro-interactions)
- Client-side cart stored in localStorage shared across pages
- Mock PayPay checkout modal (replace with real PayPay SDK/API for production)
- All main content stretches full width (no fixed max-width containers)
- Placeholder images use the format: src="https://images.unsplash.com/photo-1628232966567-788b6dd4d719?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw0fHxhJTIwZGV0YWlsZWQlMjBkZXNjcmlwdGlvbnxlbnwwfDB8fHwxNzU2NTUyNzA4fDA&ixlib=rb-4.1.0&q=80&w=1080"

Design tokens (defined in each HTML file inside a <style> tag)
- --primary-color: #1f2937 (deep charcoal)
- --secondary-color: #d4af37 (gold)
- --text-color: #111827
- --heading-font: 'Montserrat', sans-serif
- --body-font: 'Inter', sans-serif

Notes & customization
- Fonts: There is a comment at the top of each HTML file showing the Google Fonts URL to add. To enable web fonts, add the link tag with the commented URL into each page's <head>.
- Colors: Change the CSS variables in the <style> tag inside each HTML file to update theme colors across the site.
- Menu items: The menu is seeded in menu.html (client-side array). Edit the array to add/remove items and change prices.
- PayPay: The PayPay flow in this demo is a mock for demonstration. To integrate real PayPay payments, include PayPay's JS SDK on the cart page and replace the mock modal and confirmation flow with the provider's checkout calls and server-side verification.

How to run
- This is a static site. Open any of the HTML files in a browser (index.html) or host with a static server (e.g., serve, nginx, GitHub Pages).

Files
- index.html
- menu.html
- cart.html
- contact.html
- README.md

License & attribution
- Demo project. Replace placeholder images and text with your production assets. Ensure you follow PayPay's integration docs for production payments.

Enjoy! — SpiritAgent
