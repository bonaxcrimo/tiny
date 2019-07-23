# @bonaxcrimo/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@bonaxcrimo/tiny.svg)](https://www.npmjs.com/package/@bonaxcrimo/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@bonaxcrimo/tiny.svg)](https://www.npmjs.com/package/@bonaxcrimo/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @bonaxcrimo/tiny
```
## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```