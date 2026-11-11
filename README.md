# Glow Flow website

Public support website and app-ads.txt for Glow Flow by zeroshotlab.

- Website: https://glow-flow-website.vercel.app
- AdMob verification file: https://glow-flow-website.vercel.app/app-ads.txt
- Privacy policy: https://sites.google.com/view/zeroshotlab-glow-flow-privacy
- Support: hello@zeroshotlab.in

## Deployment

Vercel project `zeroshotlab/glow-flow-website` is connected to this repository. Changes to `main` automatically deploy to production. Vercel serves `public/` as a static website without a build step, using `vercel.json`.

Keep Google Play's store-listing website set to the production origin so AdMob can discover `/app-ads.txt`. Never commit private RevenueCat service-account JSON, signing keys, or app environment files.
