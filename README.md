# deplint

[![NPM version][npm-image]][npm-url]
[![Unix Build Status][travis-image]][travis-url]
[![Windows Build Status][appveyor-image]][appveyor-url]
[![Coveralls Status][coveralls-image]][coveralls-url]
[![Dependency Status][depstat-image]][depstat-url]

> fix dependencies

## Install

    npm install --save deplint

## Usage

```js
import { deplint, deplintAsync } from 'deplint';

deplint('unicorns'); // unicorns
deplintAsync('unicorns')
  .then(result => console.log(result)); // unicorns
```

## API

### deplint(input, [options])

### deplintAsync(input, [options])

Return a promise that resolves to `result`.

#### input

*Required*  
Type: `String`

Lorem ipsum.

#### options

##### foo

Type: `Boolean`  
Default: `false`

Lorem ipsum.

## License

MIT © [Vladimir Starkov](https://iamstarkov.com)

[npm-url]: https://npmjs.org/package/deplint
[npm-image]: https://img.shields.io/npm/v/deplint.svg?style=flat-square

[travis-url]: https://travis-ci.org/iamstarkov/deplint
[travis-image]: https://img.shields.io/travis/iamstarkov/deplint.svg?style=flat-square&label=unix

[appveyor-url]: https://ci.appveyor.com/project/iamstarkov/deplint
[appveyor-image]: https://img.shields.io/appveyor/ci/iamstarkov/deplint.svg?style=flat-square&label=windows

[coveralls-url]: https://coveralls.io/r/iamstarkov/deplint
[coveralls-image]: https://img.shields.io/coveralls/iamstarkov/deplint.svg?style=flat-square

[depstat-url]: https://david-dm.org/iamstarkov/deplint
[depstat-image]: https://david-dm.org/iamstarkov/deplint.svg?style=flat-square
