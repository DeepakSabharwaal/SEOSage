<p align="center">
  <a href="https://seosage.co/"><img src="assets/banner.png?v=4" alt="SEOSage app for Mac: install the desktop SEO audit software with Homebrew" width="100%"></a>
</p>

# SEOSage app for Mac: Homebrew install

[**SEOSage**](https://seosage.co/) is desktop SEO audit software for freelancers and small agencies. It crawls every page of your website with no page limits, finds the SEO problems, and exports client-ready reports. It runs on your own computer, so your crawl data stays with you.

This repository is the official [Homebrew](https://brew.sh) tap (the `brew tap` line adds this repository once) for the SEOSage app. It only holds the install file. The app itself is commercial software and its code is not published here.

## Install

<p align="center"><img src="assets/install.png?v=4" alt="Terminal showing the brew commands to install, update and remove the SEOSage app" width="80%"></p>

```sh
brew tap deepaksabharwaal/seosage https://github.com/DeepakSabharwaal/SEOSage
brew install --cask seosage
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

## What you get

Crawl a whole site, see every issue grouped by type, click one to see the pages it affects, then export a report for your client. The screens below are from a real crawl of [marketingly.org](https://marketingly.org/).

<p align="center"><img src="assets/screen-issues.png?v=4" alt="SEOSage app Issues screen listing errors, warnings and notices from a full site crawl" width="90%"></p>

<p align="center"><img src="assets/screen-report.png?v=4" alt="SEOSage app Reports screen with site health score and export to CSV, PDF or PowerPoint" width="90%"></p>

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
