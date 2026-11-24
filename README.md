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

Edit the platform status cards in `index.html` when a signed iOS beta or Android release becomes available. Link iOS users to TestFlight or the App Store; link Android users to a Google Play testing/release page or a signed APK release.

## Project status

The Android 0.1.0 APK is available for direct download from the landing page. It is not a Google Play release. The iOS app is under development; do not imply an iOS store release is ready until it has been built and published.

## Image source and rights

The Apache RTR 310 product image in `assets/apache-rtr-310-official.webp` is served by the [official TVS Apache RTR 310 website](https://www.tvsmotor.com/tvs-apache/apache-rtr-310) and is reproduced without modification. TVS Motor Company retains rights to its product images and trademarks. This fan project has no endorsement or reuse license from TVS; attribution and disclaimers do not grant permission. The app-screen visuals are HTML/CSS previews, not released-app screenshots.

## Independence

RTR Link is an independent fan-made, open-source companion for Apache RTR owners. It complements and does not replace the official TVS app. It is not affiliated with, endorsed by, or supported by TVS Motor Company. The software is experimental, provided as-is, and used at the user's own risk. Product and company names belong to their respective owners.
