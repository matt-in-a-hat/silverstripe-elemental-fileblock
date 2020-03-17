# SilverStripe Elemental File Block

[![Build Status](http://img.shields.io/travis/silverstripe/silverstripe-elemental-fileblock.svg?style=flat)](https://travis-ci.org/silverstripe/silverstripe-elemental-fileblock)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/silverstripe/silverstripe-elemental-fileblock/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/silverstripe/silverstripe-elemental-fileblock/?branch=master)
[![codecov](https://codecov.io/gh/silverstripe/silverstripe-elemental-fileblock/branch/master/graph/badge.svg)](https://codecov.io/gh/silverstripe/silverstripe-elemental-fileblock)
[![SilverStripe supported module](https://img.shields.io/badge/silverstripe-supported-0071C4.svg)](https://www.silverstripe.org/software/addons/silverstripe-commercially-supported-module-list/)

This repository contains a "file block" for the [silverstripe-elemental](https://github.com/dnadesign/silverstripe-elemental) module.

## Installation

Install using Composer:

```
composer require silverstripe/elemental-fileblock ^2.0
```

Once complete, run `dev/build` from your browser, or command line via `vendor/bin/sake dev/build`.

## Requirements

* SilverStripe CMS ^4.3
* Elemental ^4.0

## Screen Shots

#### CMS sample of some File Blocks
One image, one PDF

![CMS sample of some File Blocks](./readme-images/example-cms.png)

#### Front End sample of some File Blocks
One image, one PDF

![Front End sample of some File Blocks](./readme-images/example-frontend.png)

## Translations

The translations for this project are managed via [Transifex](https://www.transifex.com/silverstripe/silverstripe-elemental-fileblock)
and are updated automatically during the release process. To contribute, please head to the link above and get
translating!

## Versioning

This library follows [Semver](http://semver.org). According to Semver, you will be able to upgrade to any minor or patch version of this library without any breaking changes to the public API. Semver also requires that we clearly define the public API for this library.

All methods, with `public` visibility, are part of the public API. All other methods are not part of the public API. Where possible, we'll try to keep `protected` methods backwards-compatible in minor/patch versions, but if you're overriding methods then please test your work before upgrading.

## Reporting Issues

Please [create an issue](http://github.com/silverstripe/silverstripe-elemental-fileblock/issues/new) for any bugs you've found.
