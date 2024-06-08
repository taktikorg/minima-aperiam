# @taktikorg/minima-aperiam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Set` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-set-objects).

## Getting started

```sh
npm install --save @taktikorg/minima-aperiam
```

## Usage/Examples

```js
var set = new Set();
var obj = {};

set.add(obj);

set.has(obj); // true
map.has(3); // false
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/taktikorg/minima-aperiam
[npm-version-svg]: https://versionbadg.es/taktikorg/minima-aperiam.svg
[deps-svg]: https://david-dm.org/taktikorg/minima-aperiam.svg
[deps-url]: https://david-dm.org/taktikorg/minima-aperiam
[dev-deps-svg]: https://david-dm.org/taktikorg/minima-aperiam/dev-status.svg
[dev-deps-url]: https://david-dm.org/taktikorg/minima-aperiam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/minima-aperiam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/minima-aperiam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/minima-aperiam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/minima-aperiam
[codecov-image]: https://codecov.io/gh/taktikorg/minima-aperiam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/taktikorg/minima-aperiam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/taktikorg/minima-aperiam
[actions-url]: https://github.com/taktikorg/minima-aperiam/actions
