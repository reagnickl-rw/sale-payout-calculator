# Sale payout calculator

Static single-page calculator that estimates equity option proceeds in a company sale:

- Liquidation waterfall: sale price minus investor preference, divided across shares
- Two option tranches with strike prices (flags underwater tranches)
- Estimated taxes: federal marginal rate + Utah 4.5% flat tax + FICA (NSO) or no FICA (ISO)

All inputs are adjustable: sale price, federal bracket, option type, preference amount, and share count splitting the residual.

Estimates only — not tax or financial advice.

## Deploy

Pure static HTML, no build step. Deploys as-is on Vercel, Netlify, or GitHub Pages.
