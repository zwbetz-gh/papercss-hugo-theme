# PaperCSS

[![Netlify Status](https://api.netlify.com/api/v1/badges/3e3a0d5d-854f-45f2-9e30-e8a86907956a/deploy-status)](https://app.netlify.com/sites/papercss-hugo-theme/deploys)

A Hugo theme made with PaperCSS, the less formal CSS framework.

## Table of contents

- [Demo](#demo)
- [Minimum Hugo version](#minimum-hugo-version)
- [Installation](#installation)
- [Updating](#updating)
- [Run example site](#run-example-site)
- [Configuration](#configuration)
- [Favicons](#favicons)
- [Shortcodes](#shortcodes)
- [Getting help](#getting-help)
- [Credits](#credits)

## Demo

https://papercss-hugo-theme.netlify.com/

## Minimum Hugo version

Hugo version `0.48` or higher is required. View the [Hugo releases](https://github.com/gohugoio/hugo/releases) and download the binary for your OS.

## Installation

From the root of your site:

```
git submodule add https://github.com/zwbetz-gh/papercss-hugo-theme.git themes/papercss-hugo-theme
```

## Updating

From the root of your site:

```
git submodule update --remote --merge
```

## Run example site

From the root of `themes/papercss-hugo-theme/exampleSite`:

```
hugo server --themesDir ../..
```

## Configuration

Copy the `config.toml` or `config.yaml` from the [`exampleSite`](https://github.com/zwbetz-gh/papercss-hugo-theme/tree/master/exampleSite), then edit as desired. 

## Favicons

Upload your image to [RealFaviconGenerator](https://realfavicongenerator.net/) then copy-paste the generated favicon files under `static`. 

## Shortcodes

TODO link


## Getting help

If you run into an issue that isn't answered by this documentation or the [`exampleSite`](https://github.com/zwbetz-gh/papercss-hugo-theme/tree/master/exampleSite), then visit the [Hugo forum](https://discourse.gohugo.io/). The folks there are helpful and friendly. **Before** asking your question, be sure to read the [requesting help guidelines](https://discourse.gohugo.io/t/requesting-help/9132). Feel free to tag me in your question, my forum username is [@zwbetz](https://discourse.gohugo.io/u/zwbetz/summary).

## Credits

Thank you to [Rhyne Vlaservich](https://www.vlaservich.com/) for creating [PaperCSS](https://www.getpapercss.com/), and all the  [contributors](https://github.com/papercss/papercss/graphs/contributors).
