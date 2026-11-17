# Media Converter: FormatFlow | Official privacy & support pages

A static, bilingual (English / Arabic), privacy-first website whose visual system is based on **Media Converter v0.4.8 Build 21**.

## Visual source of truth
- App icon: directly downscaled from the bundled Media Converter AppIcon asset.
- Core palette: native `UrbanistTone` and `NF03UrbanistPalette` in the SwiftUI source (`#2E2E2E`, `#85B9C9`, `#FAD349`, `#F6F6F6`, and sage/porcelain fog).
- Layout: translucent 23–28pt cards, rounded pills, dark brand hero, and the 24-ray Urbanist Bloom visual.
- No hosted fonts or external trackers / scripts. Arabic typography falls back to platform fonts rather than bundling font binaries. Color and composition match the original app.
- App identity appears first; HRLX Apps appears only as the provider/contact identity inside legal material and footer.

## Recommended GitHub Pages publishing
**GitHub account:** `hrlxapp`.

**Recommended repository:** `media-converter-legal` (public) so this product has its own repository and can coexist with future apps. Creating `hrlxapp.github.io` is also technically possible but reserves the entire account-wide root site for this one app.

When GitHub Pages is enabled for this project repository at branch `main`, folder `/ (root)`, the **expected, not yet verified** URLs will be:
- Privacy: `https://hrlxapp.github.io/media-converter-legal/privacy.html`
- Arabic Privacy: `https://hrlxapp.github.io/media-converter-legal/ar/privacy.html`
- Support: `https://hrlxapp.github.io/media-converter-legal/support.html`
- Terms: `https://hrlxapp.github.io/media-converter-legal/terms.html`
- Data management: `https://hrlxapp.github.io/media-converter-legal/data.html`

These links must not be entered in App Store Connect until a deployment has completed and each URL has been checked from a public/incognito browser session.

## Publish checklist
1. Confirm the account is `hrlxapp` and verify that `media-converter-legal` is not already in use. Do not overwrite unrelated content.
2. Create the public repository and push **only the contents of this folder** to repository root (including `assets/`, `ar/`, `.nojekyll`, `style.css`). Never upload the private iOS source project here.
3. In Settings → Pages, enable `main` / `/(root)` (or equivalent supported GitHub Pages workflow).
4. Check all five key URLs in English & Arabic and make sure navigational links work without login.
5. Verify responsive and dark-mode rendering, asset loading, no Javascript trackers, no broken links, no accidental source archive.
6. Only after successful public verification, configure the App Store Connect Privacy Policy URL and Support URL.

## Current app data practices
Source policy content was checked against **Media Converter v0.4.8**. Media processing is on-device, media and job records are stored within the app, and this build has no third-party ads or analytics SDK. Commerce code exists but is disabled for this build. Re-review policy before enabling analytics, ads, cloud accounts, remote media uploads or paid purchases.

**Support contact:** hrlxapp@icloud.com  
**Prepared:** 17 November 2026  
**Status:** READY TO DEPLOY · NOT YET PUBLISHED
