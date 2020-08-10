
<div align="center">
  <br><br><br><br><br>
  <img src="https://raw.githubusercontent.com/orYoffe/megaronk/master/megaronk.svg" alt="megaronk Logo" width="400">
  <br><br><br><br><br><br><br><br>
</div>

# megaronk
## Dependencies optimization library

[![NPM](https://nodei.co/npm/megaronk.png)](https://npmjs.org/package/megaronk)

![GitHub issues](https://img.shields.io/github/issues/orYoffe/megaronk.svg)
![license](https://img.shields.io/github/license/orYoffe/megaronk.svg)
![npm bundle size](https://img.shields.io/bundlephobia/minzip/megaronk)
![npm](https://img.shields.io/npm/v/megaronk.svg)


## Install

```sh
npm install --save-dev megaronk
```

*This package is not meant to be used in production!
## Usage

### testing your dependencies

```js
const megaronk = require('megaronk');

// Testing your package.json
megaronk();
// Logs results: versions, options, scripts, json format

```

### optimize your dependencies

```js
const megaronk = require('megaronk');

// Business logic

megaronk.optimize();
// Check your console for the results

```
