# GmapVue

[![npm version](https://badge.fury.io/js/gmap-vue.svg)](https://badge.fury.io/js/gmap-vue)
[![Build Status](https://travis-ci.org/diegoazh/gmap-vue.svg?branch=master)](https://travis-ci.org/diegoazh/gmap-vue)
[![Publish](https://github.com/diegoazh/gmap-vue/workflows/publish/badge.svg)](https://github.com/diegoazh/gmap-vue/actions?query=workflow%3Apublish)
[![Documentation](https://github.com/diegoazh/gmap-vue/workflows/documentation/badge.svg)](https://github.com/diegoazh/gmap-vue/actions?query=workflow%3Adocumentation)
[![](https://data.jsdelivr.com/v1/package/npm/gmap-vue/badge)](https://www.jsdelivr.com/package/npm/gmap-vue)

## Plugin dependencies

|Name|Version|
|----|-------|
|*vue*|[![npm version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=js&r=r&type=6e&v=2.6.14&x2=0)](https://d25lcipzij17d.cloudfront.net/badge.svg?id=js&r=r&type=6e&v=2.6.14&x2=0)|
|*@googlemaps/markerclusterer*|[![npm version](https://badge.fury.io/js/@googlemaps%2Fmarkerclusterer.svg)](https://badge.fury.io/js/@googlemaps%2Fmarkerclusterer)|

## Project dependencies

|Name|Version|
|----|-------|
|*pnpm*|[![npm version](https://badge.fury.io/js/pnpm.svg)](https://badge.fury.io/js/pnpm)|
|*commitlint*|[![npm version](https://badge.fury.io/js/commitlint.svg)](https://badge.fury.io/js/commitlint)|
|*husky*|[![npm version](https://badge.fury.io/js/husky.svg)](https://badge.fury.io/js/husky)|
|*lint-staged*|[![npm version](https://badge.fury.io/js/lint-staged.svg)](https://badge.fury.io/js/lint-staged)|

## [Documentation](https://diegoazh.github.io/gmap-vue/)

The new documentation site is ready and it contains all examples for all components in the plugin.

If you find some parts of the plugin that was not documented, or if you think that some parts of the documentation are dark or can be improved please open an issue following our issue template rules.

You can use your google maps API key to use the live examples section.

We have planned to improve and grow all required documentation about the plugin.

Please follow the next link to our [documentation](https://diegoazh.github.io/gmap-vue/).

## Fork of vue2-google-maps

This is a fork of the popular vue2-google-maps. As the author of the library no longer commits to maintain the project, we forked it to develop and maintain the project.

## CONTRIBUTORS ARE WELCOME

If you have time to contribute to a rather frequently used library, feel free to make a PR!, but first please read our [contributing guide](https://github.com/diegoazh/gmap-vue/blob/master/CONTRIBUTING.md).

What's urgently needed are:

1. Better automated tests (unit with Jest, e2e with Cypress).
2. Better integration tests with the popular frameworks, especially Nuxt and Vue template
3. Migrate to VueJs v3.0
4. ~~Better documentation (examples, recommendations)~~

Please feel free to fork the project and make a PR to improve the plugin.

## Monorepo

This project uses [pnpm](https://pnpm.io/es/) to manage the plugin and documentation site.

- Clone the repository

- Run

```sh
npm install
```

or if you have installed `pnpm`

```sh
pnpm install
```

- After that you can test the component or documentation locally

- To start the documentation site locally you can run the below command, it starts the documentation page on [http://localhost:8080/](http://localhost:8080/)

```sh
pnpm run serve:docs
```

- To test the plugin you also can use a CDN like [jsdelivr](https://diegoazh.github.io/gmap-vue/#jsdelivr) or [unpkg](https://diegoazh.github.io/gmap-vue/#unpkg), in the way that the documentation shows you

## README of GmapVue

You can read the plugin's README file following [this link](https://github.com/diegoazh/gmap-vue/blob/master/packages/gmap-vue/README.md).
