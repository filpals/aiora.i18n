# aiora.i18n
This is a translation project for Aiora app for FILPAL. Everyone is welcome to contribute at https://fink.inlang.com/github.com/filpals/aiora.i18n.

## Pre-requisites
- [NodeJs](https://nodejs.org/) v18 and above

## First time

```
npm init
npx @inlang/paraglide-js@latest init
```

## Getting started

Prepare all the language files under `messages` folder. Keep all keys in `en.json` while other languages file with empty strings. Get language code from https://github.com/ladjs/i18n-locales.

```
npm install
npx @inlang/cli machine translate --project ./project.inlang
```

Now you'll have all translation done in other language files (i.e. `de.json`).

## Example of language file

```json
{
  "welcome": "Hello world {username}",
  "tooltip.submit": "Submit"
}
```

## References
1. https://inlang.com/
1. https://inlang.com/m/gerre34r/library-inlang-paraglideJs/vanilla-js-ts
1. https://inlang.com/m/2qj2w8pu/app-inlang-cli
1. https://fink2.onrender.com/
