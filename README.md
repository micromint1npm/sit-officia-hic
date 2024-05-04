# @micromint1npm/sit-officia-hic <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @micromint1npm/sit-officia-hic
```

## Usage/Examples

```js
var regexTester = require('@micromint1npm/sit-officia-hic');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@micromint1npm/sit-officia-hic
[npm-version-svg]: https://versionbadg.es/ljharb/@micromint1npm/sit-officia-hic.svg
[deps-svg]: https://david-dm.org/ljharb/@micromint1npm/sit-officia-hic.svg
[deps-url]: https://david-dm.org/ljharb/@micromint1npm/sit-officia-hic
[dev-deps-svg]: https://david-dm.org/ljharb/@micromint1npm/sit-officia-hic/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@micromint1npm/sit-officia-hic#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@micromint1npm/sit-officia-hic.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@micromint1npm/sit-officia-hic.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@micromint1npm/sit-officia-hic.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@micromint1npm/sit-officia-hic
[codecov-image]: https://codecov.io/gh/ljharb/@micromint1npm/sit-officia-hic/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@micromint1npm/sit-officia-hic/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@micromint1npm/sit-officia-hic
[actions-url]: https://github.com/micromint1npm/sit-officia-hic/actions
