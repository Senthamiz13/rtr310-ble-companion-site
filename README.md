# RTR Companion Website

Static project landing page for the RTR BLE Companion app. It is designed for GitHub Pages and lives in its own repository so website updates and app source releases can be managed independently.

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

The iOS app is under development. Android app source and installable builds are not available yet. Do not imply that a store release or binary is ready until it has been built and published.

## Independence

RTR Companion is an independent, unofficial project and is not affiliated with or endorsed by TVS Motor Company. Product and company names belong to their respective owners.
