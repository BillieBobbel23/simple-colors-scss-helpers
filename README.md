# simple-colors-scss-helpers

Simple-colors-scss-helpers are some mixins and utilities that provide support for [simple-colors-scss](https://github.com/BillieBobbel23/simple-colors-scss).

![version](https://img.shields.io/npm/v/simple-colors-scss.svg)
![size](https://img.shields.io/bundlephobia/minzip/simple-colors-scss)
![stats](https://david-dm.org/BillieBobbel23/simple-colors-scss/status.svg)


## Installation

Install the package via NPM:

`` npm install simple-colors-scss-helpers --save ``

Import the NPM package in your stylesheet after simple-colors-scss:
```
@import 'your_project/node_modules/simple-colors-scss/core';
@import 'your_project/node_modules/simple-colors-scss-helpers/helpers';
```

## Helper mixins

Helper mixins are included for some simple tasks like setting backgrounds, text- and border colors and adding modularity.

### color()

Sets color attribute with ``$key``:

```
  @include color('white');
```

### bg()

Sets ``background-color`` attribute:

```
  @include bg('white');
```

### border-color()

Sets ``border-color`` attribute:

```
  @include border-color('white');
  // or
  @include b-color('white');
```

### shadow()

Sets ``box-shadow`` attribute:

```
  @include shadow('white');
```