# npmdoc-espree

#### api documentation for  [espree (v3.4.1)](https://github.com/eslint/espree)  [![npm package](https://img.shields.io/npm/v/npmdoc-espree.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-espree) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-espree.svg)](https://travis-ci.org/npmdoc/node-npmdoc-espree)

#### An Esprima-compatible JavaScript parser built on Acorn

[![NPM](https://nodei.co/npm/espree.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/espree)

- [https://npmdoc.github.io/node-npmdoc-espree/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-espree/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-espree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-espree/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-espree/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-espree/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "espree",
    "description": "An Esprima-compatible JavaScript parser built on Acorn",
    "author": "Nicholas C. Zakas <nicholas+npm@nczconsulting.com>",
    "homepage": "https://github.com/eslint/espree",
    "main": "espree.js",
    "version": "3.4.1",
    "files": [
        "lib",
        "espree.js"
    ],
    "engines": {
        "node": ">=0.10.0"
    },
    "repository": "eslint/espree",
    "bugs": {
        "url": "http://github.com/eslint/espree.git"
    },
    "license": "BSD-2-Clause",
    "dependencies": {
        "acorn": "^5.0.1",
        "acorn-jsx": "^3.0.0"
    },
    "devDependencies": {
        "browserify": "^7.0.0",
        "chai": "^1.10.0",
        "eslint": "^2.0.0-beta.1",
        "eslint-config-eslint": "^3.0.0",
        "eslint-release": "^0.10.0",
        "esprima": "latest",
        "esprima-fb": "^8001.2001.0-dev-harmony-fb",
        "istanbul": "~0.2.6",
        "json-diff": "~0.3.1",
        "leche": "^1.0.1",
        "mocha": "^2.0.1",
        "regenerate": "~0.5.4",
        "shelljs": "^0.3.0",
        "shelljs-nodecli": "^0.1.1",
        "unicode-6.3.0": "~0.1.0"
    },
    "keywords": [
        "ast",
        "ecmascript",
        "javascript",
        "parser",
        "syntax",
        "acorn"
    ],
    "scripts": {
        "generate-regex": "node tools/generate-identifier-regex.js",
        "test": "npm run-script lint && node Makefile.js test",
        "lint": "node Makefile.js lint",
        "release": "eslint-release",
        "ci-release": "eslint-ci-release",
        "gh-release": "eslint-gh-release",
        "alpharelease": "eslint-prelease alpha",
        "betarelease": "eslint-prelease beta",
        "browserify": "node Makefile.js browserify"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
