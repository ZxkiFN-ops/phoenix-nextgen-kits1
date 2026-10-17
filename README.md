# Phoenix NextGen Kits — preview prototype

This is a static storefront prototype for preview/development. It includes:
- Responsive black-and-gold storefront design
- Product cards, category filters, size selection and interactive cart
- Demo-only checkout notice
- Admin dashboard visual placeholder

## Deploy to Vercel
1. Upload `index.html` to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. For a plain static site, Vercel can deploy the HTML without a build command. If asked for a framework preset, choose **Other** and leave the build command empty.
4. Deploy and open the generated preview URL.

## Important
This is a front-end prototype only. It does NOT have a secure admin login, persistent product/order database, inventory management, shipping/tax configuration, or Stripe integration. Checkout is a demo alert and takes no payment. Do not use it to accept real orders. Before launch, add a secure server-side backend, database, authentication/authorization, Stripe Checkout integration and verified payment webhooks. Replace placeholder prices/illustrations with approved product data and actual club imagery.
