[npm-image]: https://img.shields.io/npm/v/node-simple-base64.svg
[npm-url]: https://www.npmjs.com/package/node-simple-base64

# node-simple-base64 [![npm][npm-image]][npm-url]
Simple base64 encode/decode for nodeJS

## Installation
```shell
npm install node-simple-base64
```

## Usage (with CommonJS)
```javascript
const base64 = require('node-simple-base64');

const encodedKorean = base64.encode('안녕하세요'); // -> 7JWI64WV7ZWY7IS47JqU
base64.decode(encodedKorean); // -> 안녕하세요

const encoded = base64.encode('Hello World'); // -> SGVsbG8gV29ybGQ=
base64.decode(encoded); // -> Hello World
```