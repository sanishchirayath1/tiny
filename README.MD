# @sanishchirayath/tiny

[![npm (scoped)](https://img.shields.io/npm/v/%40sanishchirayath/tiny)](https://github.com/sanishchirayath1/tiny)

[![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/%40sanishchirayath/tiny)](https://github.com/sanishchirayath1/tiny)

The tiniest package ever.

## Install

```
$ npm install @sanishchirayath/tiny
```

## Usage

```js
const tiny = require("@sanishchirayath/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(123);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:31)
//    at <anonymous>:1:1
```
