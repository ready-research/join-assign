[![code style](https://img.shields.io/badge/code_style-classic-blue.svg)](http://diogoeichert.github.io/eslint-config-classic)
[![downloads](https://img.shields.io/npm/dt/join-assign.svg)](https://www.npmjs.com/package/join-assign)
[![license](https://img.shields.io/github/license/diogoeichert/join-assign.svg)](LICENSE)
[![npm version](https://img.shields.io/npm/v/join-assign.svg)](https://www.npmjs.com/package/join-assign)

# join-assign
Deep assign to target from source, also performs distinct concat.

## Usage
```
const join = require("join-assign");

const source = {
  letters: [
    "c",
    "d"
  ]
};

const target = {
  letters: [
    "a",
    "b"
  ]
};

join.assign(target, source);

const a = [1, 2, 3, 4, 5];
const b = [4, 5, 6, 7, 8];

join.concat(a, b);
```
