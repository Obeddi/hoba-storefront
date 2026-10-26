HOBA storefront prototype (static site)

Deploy on Vercel:
1. vercel.com → Add New → Project → "Deploy without Git" (or drag this folder onto the dashboard).
2. Framework preset: Other. Output directory: public. No build command.
3. Deploy. The site is a single page (public/index.html) plus image sprite sheets.

Everything runs in the browser; there is no server code. Bag, wishlist and theme choice are stored in localStorage.
