# @hishprorg/fugit-at <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

`[].map(f)` for older browsers

# example

``` js
var map = require('@hishprorg/fugit-at');
var letters = map([97,98,99], function (c) {
	return String.fromCharCode(c);
});
console.log(letters.join(''));
```

output:

```
abc
```

# methods

``` js
var map = require('@hishprorg/fugit-at')
```

## var ys = map(xs, f)

Create a new array `ys` by applying `f(xs[i], i, xs)` to each element in `xs` at
index `i`.

# install

With [npm](https://npmjs.org) do:

```
npm install @hishprorg/fugit-at
```

# license

MIT

[package-url]: https://npmjs.org/package/@hishprorg/fugit-at
[npm-version-svg]: https://versionbadg.es/ljharb/@hishprorg/fugit-at.svg
[deps-svg]: https://david-dm.org/ljharb/@hishprorg/fugit-at.svg
[deps-url]: https://david-dm.org/ljharb/@hishprorg/fugit-at
[dev-deps-svg]: https://david-dm.org/ljharb/@hishprorg/fugit-at/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hishprorg/fugit-at#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishprorg/fugit-at.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/fugit-at.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/fugit-at.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/fugit-at
[codecov-image]: https://codecov.io/gh/ljharb/@hishprorg/fugit-at/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hishprorg/fugit-at/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hishprorg/fugit-at
[actions-url]: https://github.com/hishprorg/fugit-at/actions
