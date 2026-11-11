# Home Invest Thursday Event

Static landing page for the Home Invest cost segregation webinar.

The page is at `public/cost-seg-webinar/index.html`. The Worker serves static assets from `public/` and declares the `homeinvest.com/cost-seg-webinar` route in `wrangler.jsonc`.

## Cloudflare deployment

In Cloudflare Workers & Pages, import this repository through Workers Builds. Leave the build command empty and use `npx wrangler deploy` as the deploy command. Pushes to `main` will deploy automatically after the repository is connected. The Cloudflare account must permit the Worker to create routes on the `homeinvest.com` zone.

