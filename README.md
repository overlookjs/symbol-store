[![NPM version](https://img.shields.io/npm/v/@overlook/symbol-store.svg)](https://www.npmjs.com/package/@overlook/symbol-store)
[![Dependency Status](https://img.shields.io/david/overlookjs/symbol-store.svg)](https://david-dm.org/overlookjs/symbol-store)
[![Dev dependency Status](https://img.shields.io/david/dev/overlookjs/symbol-store.svg)](https://david-dm.org/overlookjs/symbol-store) [![Greenkeeper badge](https://badges.greenkeeper.io/overlookjs/symbol-store.svg)](https://greenkeeper.io/)

# Overlook framework symbol store

Part of the [Overlook framework](https://overlookjs.github.io/).

## Usage

Singleton symbol store for [Overlook framework](https://overlookjs.github.io/).

It exports an empty object which can be used to store symbols defined by `Route` class extensions etc.

This module will never be updated, so `require('@overlook/symbol-store')` will always return the same object.

Should not be imported or accessed directly. Other parts of the framework use this internally.

## Changelog

See [changelog.md](https://github.com/overlookjs/symbol-store/blob/master/changelog.md)

## Issues

If you discover a bug, please raise an issue on Github. https://github.com/overlookjs/symbol-store/issues

## Contribution

Pull requests are very welcome. Please:

* ensure all tests pass before submitting PR
* add tests for new features
* document new functionality/API additions in README
* do not add an entry to Changelog (Changelog is created when cutting releases)
