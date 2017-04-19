# npmdoc-nplaym

#### api documentation for  [nplaym (v1.3.8)](https://github.com/JonathanUsername/nplaym#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-nplaym.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nplaym) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nplaym.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nplaym)

#### A wrapper for npm so you can play a Space-Invaders-a-like game while installing.

[![NPM](https://nodei.co/npm/nplaym.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nplaym)

- [https://npmdoc.github.io/node-npmdoc-nplaym/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nplaym/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nplaym/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nplaym/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nplaym/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nplaym/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan King"
    },
    "bin": {
        "nplaym": "./bin/nplaym"
    },
    "bugs": {
        "url": "https://github.com/JonathanUsername/nplaym/issues"
    },
    "dependencies": {
        "child_pty": "~3.0.1",
        "colors": "~1.1.2",
        "extend": "~3.0.0",
        "keypress": "~0.2.1",
        "lodash": "~4.6.1",
        "nan": "~2.2.0",
        "node-terminal": "~0.1.1"
    },
    "description": "A wrapper for npm so you can play a Space-Invaders-a-like game while installing.",
    "devDependencies": {
        "babel-cli": "~6.6.5",
        "babel-preset-es2015": "~6.6.0",
        "babel-preset-es2015-rollup": "~1.1.1",
        "babelify": "~7.2.0",
        "rollup-plugin-babel": "~2.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fe2d9e3e091283d5842f8c35094d6ce504c24cd9",
        "tarball": "https://registry.npmjs.org/nplaym/-/nplaym-1.3.8.tgz"
    },
    "gitHead": "d1e35fe78634e10e3b45b0ac41289453acc93a3c",
    "homepage": "https://github.com/JonathanUsername/nplaym#readme",
    "license": "ISC",
    "maintainers": [
        {
            "name": "jonathanking"
        }
    ],
    "name": "nplaym",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/JonathanUsername/nplaym.git"
    },
    "scripts": {
        "build": "rollup -i src/index.js -o bin/nplaym --banner '#!/usr/bin/env node' --config rollup.config.js",
        "dev": "babel --source-maps --out-dir lib/ src/ --watch",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "1.3.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
