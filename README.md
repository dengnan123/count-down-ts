# count-down-ts

[![NPM version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
![][travis-url]
[![Coverage Status][coverage-image]][coverage-url]
![][david-url]
![][dt-url]
[![code style: prettier][prettier-image]][prettier-url]
![][license-url]

Countdown has timer, count, clear features. Test covered 100%.

## Install

### npm

```bash
npm install count-down-ts --save
```

### yarn

```bash
yarn add count-down-ts --save
```

### bower

```bash
bower install count-down-ts --save
```

## Import

### ES2015

```typescript
import countdown from 'count-down-ts'
```

### CommonJS

```javascript
const countdown = require('count-down-ts')
```

### script

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>DEMO</title>
  </head>
  <body>
    <script type="text/javascript" src="node_modules/count-down-ts/dist/count-down-ts.js"></script>
    <script type="text/javascript">
      var countdown = window.countdown
    </script>
  </body>
</html>
```

## Usage

```typescript
// init countdown
countdown.start(60, 0, c => console.log(c))

OR

countdown.start()

// cleat countdown setTimeout & count & timer
countdown.clear()

// countdown setTimeout return value
countdown.timer

// countdown current number
countdown.count
```

### accept-expression

#### countdown.start(count, down, callback)

`count`: Default 60, type number. Tips: count must greater than down, or equal down.

`down`: Default 0, type number.

`callback`: Type (c: number) => void.

## LICENSE

[GPL v3 License](https://raw.githubusercontent.com/sanshuiwang/count-down-ts/master/LICENSE)

[npm-url]: https://npmjs.org/package/count-down-ts
[npm-image]: https://badge.fury.io/js/count-down-ts.png
[travis-image]: https://www.travis-ci.org/sanshuiwang/count-down-ts.svg?branch=master
[travis-url]: https://travis-ci.com/sanshuiwang/count-down-ts
[coverage-image]: https://coveralls.io/repos/github/sanshuiwang/count-down-ts/badge.svg?branch=master
[coverage-url]: https://coveralls.io/github/sanshuiwang/count-down-ts
[david-url]: https://david-dm.org/sanshuiwang/count-down-ts.png
[dt-url]: https://img.shields.io/npm/dt/count-down-ts.svg
[license-url]: https://img.shields.io/npm/l/count-down-ts.svg
[prettier-image]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg
[prettier-url]: https://github.com/prettier/prettier
