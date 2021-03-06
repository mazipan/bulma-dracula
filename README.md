# 😈 bulma-dracula

![Bulma Dracula](https://img.shields.io/badge/bulma-dracula-purple.svg) ![Bulma](https://img.shields.io/badge/bulma-v0.9.0-00d1b2.svg) [![Travis](https://img.shields.io/travis/mazipan/bulma-dracula.svg)](https://travis-ci.org/mazipan/bulma-dracula) [![Bulma Dracula NPM](https://img.shields.io/npm/v/bulma-dracula.svg)](https://www.npmjs.com/package/bulma-dracula) ![Download](https://img.shields.io/npm/dt/bulma-dracula.svg) ![Dependencies](https://img.shields.io/david/mazipan/bulma-dracula.svg)

> Bulma css with Dracula dark color themes

## Homepage

[https://mazipan.github.io/bulma-dracula/](https://mazipan.github.io/bulma-dracula/)

## Screenshoot

![Screenshoot](screenshoot.png)

## Usage

Install dependency:

```bash
$ yarn add bulma-dracula
# OR
$ npm i bulma-dracula
```

Import in your `.scss` files:

```scss
// this is already bundled with bulma.css
@import "~bulma-dracula/src/bulma-dracula.scss";
```

CDN on `unpkg`:

[https://unpkg.com/bulma-dracula@1.0.0/dist/bulma-dracula.css](https://unpkg.com/bulma-dracula@1.0.0/dist/bulma-dracula.css)

Change `1.0.0` with latest version or you can just hit [https://unpkg.com/bulma-dracula](https://unpkg.com/bulma-dracula)

## Override Variables

Bulma Dracula already bundled with Bulma CSS, that's why it can not be overriden.
You can override with only use our SCSS variable definitions.

- Install Bulma and Bulma Dracula seperately:

```bash
$ yarn add bulma bulma-dracula
# OR
$ npm i bulma bulma-dracula
```

- Use Bulma Dracula variables:

```scss
@import "~bulma-dracula/src/bulma-dracula-vars.scss";
// You can override the default Bulma Dracula variables here
@import "~bulma/bulma";
```

## Dracula Color Palette

This repo will override these variables https://bulma.io/documentation/customize/variables/ with below palletes:

Palette      | Hex       | 
---          | ---       |
Background   | `#282a36` | 
Current Line | `#44475a` |
Selection    | `#44475a` |
Foreground   | `#f8f8f2` |
Comment      | `#6272a4` |
Cyan         | `#8be9fd` |
Green        | `#50fa7b` | 
Orange       | `#ffb86c` |
Pink         | `#ff79c6` |
Purple       | `#bd93f9` |
Red          | `#ff5555` |
Yellow       | `#f1fa8c` |


## Support me

- 👉 🇮🇩 [Trakteer](https://trakteer.id/mazipan?utm_source=github)
- 👉 🌍 [BuyMeACoffe](https://www.buymeacoffee.com/mazipan?utm_source=github)
- 👉 🌍 [Paypal](https://www.paypal.me/mazipan?utm_source=github)
- 👉 🌍 [Ko-Fi](https://ko-fi.com/mazipan)

---

Copyright © 2019, Released under MIT license. By Irfan Maulana from 🇮🇩
