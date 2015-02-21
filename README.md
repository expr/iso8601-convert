# iso8601-convert
> Convert between ISO8601 strings and Date objects

Alternative to `Date.parse()` with support for leap seconds. A fork of [calmh/node-iso8601](https://github.com/calmh/node-iso8601) adding extra error handling.

## Installation

    npm install iso8601-convert

## Usage

```js
var iso8601 = require('iso8601-convert')

console.log(iso8601.toDate(''))
console.log(iso8601.fromDate(Date.now()))
```
