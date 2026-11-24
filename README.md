# RTR Link Website

Static project landing page for the RTR Link app. It is designed for GitHub Pages and lives in its own repository so website updates and app source releases can be managed independently.

The site uses a side-profile motorcycle silhouette with restrained theme accents as the RTR Link mark. The transparent image at `assets/rtr-link-bike.png` also serves as the favicon. It is fan-project artwork and does not use the TVS or Apache logo.

## Preview locally

Open `index.html` in a browser, or serve the folder with any static web server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

The site is plain HTML and CSS. In the GitHub repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. GitHub Pages publishes the site at the repository's Pages URL.

## Updating app availability

Edit the platform status cards in `index.html` when an iOS or Android release changes. The [iOS installation guide](ios-install.html) documents running a development build on a personal iPhone through Xcode. Link Android users to a Google Play testing/release page or a signed APK release.

## Features, roadmap, and releases

The landing page lists current app behavior, platform-specific limitations, planned work, and versioned release notes. Keep those descriptions aligned with the app source and its version metadata. Do not describe roadmap items as available features or development builds as store releases.

The funding section is informational only until a real payout profile or payment link is configured. Never add a donation button that does not lead to an active, verified account.

## Project status

The Android 0.1.0 APK is available for direct download from the landing page. It is not a Google Play release. iPhone owners can build and install the iOS app on their own device with Xcode and a free Apple Account; the Personal Team signing expires after 7 days and must be refreshed from Xcode. There is no public iOS binary or TestFlight build. Broader iOS distribution requires Apple Developer Program membership. Current project metadata lists iOS version 1.0, build 1; that is an Xcode development build, not a public release.

## Image source and rights

The Apache RTR 310 product image in `assets/apache-rtr-310-official.webp` is served by the [official TVS Apache RTR 310 website](https://www.tvsmotor.com/tvs-apache/apache-rtr-310) and is reproduced without modification. TVS Motor Company retains rights to its product images and trademarks. This fan project has no endorsement or reuse license from TVS; attribution and disclaimers do not grant permission. The app-screen visuals are HTML/CSS previews, not released-app screenshots.

## Independence

RTR Link is an independent fan-made, open-source companion for Apache RTR owners. It complements and does not replace the official TVS app. It is not affiliated with, endorsed by, or supported by TVS Motor Company. The software is experimental, provided as-is, and used at the user's own risk. Product and company names belong to their respective owners.
