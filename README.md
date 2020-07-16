[![GitHub issues](https://img.shields.io/badge/npm-v2.0.0-lightgrey)](https://github.com/Naveen7892/sample-npm-package)

## Removes all spaces from a string.

### Install
> $ npm install @bamblehorse/tiny

### Usage
```
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

### Note:

### This is a sample-npm-package
Publishing sample NPM package following the tutorial https://www.freecodecamp.org/news/how-to-make-a-beautiful-tiny-npm-package-and-publish-it-2881d4307f78/

# Commands used:

    > npm adduser
    or
    > npm login

    > npm publish --access=public