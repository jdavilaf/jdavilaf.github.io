# JD Apps — GitHub Pages

This repository publishes the developer website at https://jdavilaf.github.io/ and the AdMob authorization file at https://jdavilaf.github.io/app-ads.txt.

## Publish
1. Create a **public** GitHub repository named exactly `jdavilaf.github.io` under the `jdavilaf` account.
2. Upload `index.html`, `app-ads.txt`, and `README.md` to the repository root.
3. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, `main`, `/ (root)`, then save.
4. Wait for deployment. Check both URLs above; `app-ads.txt` must display a single plain-text line.
5. In App Store Connect, set the **Marketing URL** of each relevant app to `https://jdavilaf.github.io/`, leaving existing support URLs unchanged.
6. Once the developer website appears in the public App Store listing, use **Check for updates** in AdMob's app-ads.txt verification section.

## Future apps
Add new app cards to `index.html`. If all apps use the same AdMob publisher, the existing line in `app-ads.txt` does not need to be repeated. For additional authorized ad sellers, add their exact lines separately.

## Notes
The Pulse Loop App Store URL is based on App Store ID `6760823635`; check it after publication. ONE SECOND is listed as coming soon without an unverified store link.
