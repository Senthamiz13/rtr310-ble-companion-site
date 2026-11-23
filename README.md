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

## Image credits

The Apache RTR 310 photograph in `assets/apache-rtr-310.jpg` is by [Crazyranga](https://commons.wikimedia.org/wiki/User:Crazyranga), sourced from [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Apache_rtr_310.jpg), and licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The photograph is shown unmodified. The app-screen visuals are HTML/CSS interface previews based on the project UI, not screenshots from a released app.

## Independence

RTR Companion is an independent, unofficial project and is not affiliated with or endorsed by TVS Motor Company. Product and company names belong to their respective owners.
