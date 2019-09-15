# simple-colors-scss-helpers

Simple-colors-scss-helpers are some mixins and utilities that provide support for [simple-colors-scss](https://github.com/BillieBobbel23/simple-colors-scss).

![statsdev](	https://img.shields.io/npm/v/simple-colors-scss-helpers.svg)
![stats](https://david-dm.org/BillieBobbel23/simple-colors-scss/status.svg)
![statsdev](https://david-dm.org/BillieBobbel23/ simple-colors-scss/dev-status.svg)


## Installation

Install the package via NPM:

`` npm install simple-colors-scss-helpers --save-dev ``

Import the NPM package in your stylesheet after simple-colors-scss:
```
@import 'your_project/node_modules/simple-colors-scss/core';
@import 'your_project/node_modules/simple-colors-scss-helpers/helpers';
```

## Helper mixins

Helper mixins are included for some simple tasks like setting backgrounds, text- and border colors and adding modularity.

```
.element{
  @include color('white');
  @include bg('black');
  @include border-color('test');
}
```
