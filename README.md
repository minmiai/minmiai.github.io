# Minmi website

Standalone static website for Minmi, modeled on the root-based GitHub Pages setup used by [Paint.Cross](https://paintcross.github.io/).

## Local preview

Run from this directory:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000>.

## Publish with GitHub Pages

Create the `minmiai.github.io` repository under the `minmiai` organization, push this project to its `main` branch, then set **Settings → Pages → Deploy from a branch → `main` / `(root)`**. The expected address is <https://minmiai.github.io/>. No build step is required.

The signed Mac app and checksum should be attached to versioned releases in [Joonk72/Minmi](https://github.com/Joonk72/Minmi/releases). Once App Store and Play Store listings are live, replace the phone app/source button with their direct links.
