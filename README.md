# TrueCost website

The public pages for the TrueCost iPhone app, published with GitHub Pages at
https://truecost.evenstickerco.com/

- `index.html`: the privacy policy. Generated from `src/data/privacy-policy.json` in the app's repository by `scripts/build-privacy-page.mjs`.
- `.well-known/apple-app-site-association`: tells iPhones that email links to `/auth-callback/` open only in TrueCost.
- `auth-callback/index.html`: shown if one of those links is opened in a browser instead.
- `.nojekyll`: makes GitHub Pages publish the `.well-known` folder.

Everything here is a copy of the `website/` folder in the app's repository. Don't edit it by hand.
