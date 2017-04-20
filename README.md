# npmdoc-bigpipe

#### api documentation for  [bigpipe (v0.9.14)](http://bigpipe.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-bigpipe.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bigpipe) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bigpipe.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bigpipe)

#### Bigpipe a radical new web framework for Node.js that's inspired by Facebook's bigpipe concept.

[![NPM](https://nodei.co/npm/bigpipe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bigpipe)

- [https://npmdoc.github.io/node-npmdoc-bigpipe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bigpipe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bigpipe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bigpipe/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bigpipe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bigpipe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bigpipe",
    "version": "0.9.14",
    "description": "Bigpipe a radical new web framework for Node.js that's inspired by Facebook's bigpipe concept.",
    "main": "index.js",
    "engine": "node >= 0.10.0",
    "scripts": {
        "100%": "istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100",
        "test": "mocha $(find test -name '*.test.js')",
        "watch": "mocha --watch $(find test -name '*.test.js')",
        "coverage": "istanbul cover ./node_modules/.bin/_mocha -- $(find test -name '*.test.js')",
        "test-travis": "istanbul cover node_modules/.bin/_mocha --report lcovonly -- $(find test -name '*.test.js')"
    },
    "dependencies": {
        "404-pagelet": "1.0.x",
        "500-pagelet": "1.0.x",
        "async": "0.9.x",
        "asyncemit": "1.0.x",
        "bigpipe.js": "0.9.x",
        "bootstrap-pagelet": "1.0.x",
        "browserify": "9.0.x",
        "create-server": "0.0.x",
        "demolish": "1.0.x",
        "diagnostics": "0.0.x",
        "eventemitter3": "0.1.x",
        "fabricator": "0.5.x",
        "fusing": "1.0.x",
        "mkdirp": "0.5.x",
        "smithy": "0.6.x",
        "supply": "0.0.x",
        "temper": "0.3.x",
        "zipline": "1.0.x"
    },
    "devDependencies": {
        "assume": "1.2.x",
        "fittings": "1.2.x",
        "istanbul": "0.3.x",
        "mocha": "2.2.x",
        "pagelet": "0.9.x",
        "pre-commit": "1.0.x"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/bigpipe/bigpipe.git"
    },
    "bugs": {
        "url": "https://github.com/bigpipe/bigpipe/issues"
    },
    "keywords": [
        "pagelet",
        "pagelets",
        "realtime",
        "real-time",
        "framework",
        "modular",
        "bigpipe"
    ],
    "author": "Arnout Kazemier",
    "license": "MIT",
    "homepage": "http://bigpipe.io"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
