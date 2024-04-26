# @wemnyelezxnpm/eveniet-cumque-quidem <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@wemnyelezxnpm/eveniet-cumque-quidem');
const Eval = require('@wemnyelezxnpm/eveniet-cumque-quidem/eval');
const Range = require('@wemnyelezxnpm/eveniet-cumque-quidem/range');
const Ref = require('@wemnyelezxnpm/eveniet-cumque-quidem/ref');
const Syntax = require('@wemnyelezxnpm/eveniet-cumque-quidem/syntax');
const Type = require('@wemnyelezxnpm/eveniet-cumque-quidem/type');
const URI = require('@wemnyelezxnpm/eveniet-cumque-quidem/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@wemnyelezxnpm/eveniet-cumque-quidem
[npm-version-svg]: https://versionbadg.es/ljharb/@wemnyelezxnpm/eveniet-cumque-quidem.svg
[deps-svg]: https://david-dm.org/ljharb/@wemnyelezxnpm/eveniet-cumque-quidem.svg
[deps-url]: https://david-dm.org/ljharb/@wemnyelezxnpm/eveniet-cumque-quidem
[dev-deps-svg]: https://david-dm.org/ljharb/@wemnyelezxnpm/eveniet-cumque-quidem/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@wemnyelezxnpm/eveniet-cumque-quidem#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@wemnyelezxnpm/eveniet-cumque-quidem.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@wemnyelezxnpm/eveniet-cumque-quidem.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@wemnyelezxnpm/eveniet-cumque-quidem.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@wemnyelezxnpm/eveniet-cumque-quidem
[codecov-image]: https://codecov.io/gh/ljharb/@wemnyelezxnpm/eveniet-cumque-quidem/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@wemnyelezxnpm/eveniet-cumque-quidem/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@wemnyelezxnpm/eveniet-cumque-quidem
[actions-url]: https://github.com/wemnyelezxnpm/eveniet-cumque-quidem/actions
