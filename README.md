# PilkixApps website

The developer website for PilkixApps apps, served by GitHub Pages from this repository.

- `index.html`: the home page, one card per app.
- `style.css`: the look shared by every page (light and dark).
- `app-ads.txt`: AdMob reads it here, at the root of the site, for every app in the App Store
  whose Marketing URL is on this site. One line covers all apps of the same AdMob account; add a
  line only for another ad network.
- `fingadruma/`: the Fingadruma page and its icon.

## Adding an app

1. Copy the `fingadruma` folder to a new folder named after the app, for example `newapp/`, and
   change the texts, links and `icon.png` (256×256) in `newapp/index.html`.
2. In `index.html`, copy the Fingadruma card and point it at `newapp/`.
3. In App Store Connect, set the new app's Marketing URL to this site's address.
