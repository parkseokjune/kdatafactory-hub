# kdatafactory — hub

The landing page for the **kdatafactory** suite: pay-per-result scrapers that turn
Korean platform data (K-beauty, K-fashion, K-pop, crowdfunding, resale, local) into
clean English JSON.

- **Live site:** https://parkseokjune.github.io/kdatafactory-hub/
- **Actors:** https://apify.com/kdatafactory

Single self-contained `index.html` (no build step, no dependencies), served by
GitHub Pages. Edit `index.html` and push to deploy.

## Custom domain

To serve this from a branded domain (e.g. `kdatafactory.dev`):
1. Add a `CNAME` file containing the domain.
2. At the registrar, point the domain at GitHub Pages (CNAME → `parkseokjune.github.io`,
   or the four A records for an apex domain).
3. Enable *Enforce HTTPS* in the repo's Pages settings.
