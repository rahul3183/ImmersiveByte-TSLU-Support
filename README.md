# Truck Simulator Legends support pages

This folder contains self-contained support and privacy pages for Truck Simulator Legends on iOS and Truck Simulator Legends: USA on Android.

## Files

- `index.html` — use as the App Store **Support URL**.
- `privacy-policy-ios.html` — use as the App Store **Privacy Policy URL** for Truck Simulator Legends on iOS.
- `privacy-policy.html` — keep this URL for the Android privacy policy.
- `immersivebyte-logo.png` — shared header logo used by the pages.

The pages use `immersivebyte@gmail.com`, matching the currently published privacy policy. Review the support steps and policy whenever the game’s SDKs or data practices change.

## Publish with GitHub Pages

1. Copy all three HTML files and `immersivebyte-logo.png` into the root of the public GitHub repository, or into the repository's `/docs` folder.
2. In the GitHub repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the folder containing the file (`/root` or `/docs`), then save.
5. Open the generated `https://<username>.github.io/<repository>/` address in a private browser window.
6. Use the generated root address as the App Store Support URL. Use the same address followed by `/privacy-policy-ios.html` as the iOS Privacy Policy URL. Keep `/privacy-policy.html` for Android.

For the current repository, the expected addresses are:

```text
https://rahul3183.github.io/ImmersiveByte-TSLU-Support/
https://rahul3183.github.io/ImmersiveByte-TSLU-Support/privacy-policy-ios.html
https://rahul3183.github.io/ImmersiveByte-TSLU-Support/privacy-policy.html
```

## Use with Google Sites

Google Sites does not directly host an uploaded HTML project. Either:

- recreate the same sections in a Google Sites page and publish it; or
- publish this page with GitHub Pages, then use **Insert → Embed → By URL** in Google Sites.

For the App Store Support URL, the direct GitHub Pages URL is simpler and avoids displaying the page inside another site.
