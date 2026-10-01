# SEOSage app for Mac: Homebrew install

[**SEOSage**](https://seosage.co/) is desktop SEO audit software for freelancers and small agencies. It crawls every page of your website with no page limits, finds the SEO problems, and exports client-ready reports. It runs on your own computer, so your crawl data stays with you.

This repository is the official [Homebrew](https://brew.sh) tap for the SEOSage app. It only holds the install file. The app itself is commercial software and its code is not published here.

## Install

```sh
brew install --cask deepaksabharwaal/seosage/seosage
```

Update later:

```sh
brew upgrade --cask seosage
```

Uninstall:

```sh
brew uninstall --cask seosage
```

Works on Apple Silicon (M1, M2, M3, M4) and Intel Macs. Homebrew picks the right file for your Mac.

## Licence

SEOSage needs a licence key, and every plan starts with a 14-day free trial. See [pricing](https://seosage.co/pricing/). Paste the key when the app first opens.

## Links

- Website: [seosage.co](https://seosage.co/)
- Download for Mac and Windows: [seosage.co/download](https://seosage.co/download/)
- Features: [seosage.co/features](https://seosage.co/features/)
- SEO crawler: [seosage.co/seo-crawler](https://seosage.co/seo-crawler/)
- Free SEO tools: [seosage.co/tools](https://seosage.co/tools/)
- What's new: [seosage.co/changelog](https://seosage.co/changelog/)
- Support: [hello@seosage.co](mailto:hello@seosage.co)

## About this tap

The cask downloads the official installer from `seosage.co` and checks its SHA-256 before installing. SEOSage is not yet Apple-notarised, so the cask clears the macOS download warning for you after install. Windows users: use the installer on the [download page](https://seosage.co/download/).
