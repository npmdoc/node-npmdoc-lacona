# npmdoc-lacona [![npm package](https://img.shields.io/npm/v/npmdoc-lacona.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lacona) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lacona.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lacona)

api documentation for  [lacona (v0.39.0)](https://github.com/lacona/lacona)
#### Natural Language Parsing Framework

[![NPM](https://nodei.co/npm/lacona.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lacona)

- [https://npmdoc.github.io/node-npmdoc-lacona/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lacona/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lacona/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lacona/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lacona/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lacona/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brandon Horst",
        "url": "http://github.com/brandonhorst"
    },
    "bugs": {
        "url": "https://github.com/lacona/lacona/issues"
    },
    "dependencies": {
        "babel-runtime": "^5.8.34",
        "lacona-phrase": "^0.9.1",
        "lodash": "^3.10.1",
        "smart-split": "^1.0.2"
    },
    "deprecated": "lacona is no longer used. For the Lacona addon cli tool, install 'lacona-cli'. For the language parser, install 'elliptical'. ",
    "description": "Natural Language Parsing Framework",
    "devDependencies": {
        "babel": "^5.8.34",
        "chai": "^3.4.1",
        "mocha": "^2.3.4",
        "rimraf": "^2.4.4",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "aba6e468407501458758d14f8de748e8cb633e71",
        "tarball": "https://registry.npmjs.org/lacona/-/lacona-0.39.0.tgz"
    },
    "gitHead": "27fca395d1306df62ee081834b0833d794cbb19c",
    "homepage": "https://github.com/lacona/lacona",
    "keywords": [
        "lingustic",
        "natural",
        "language",
        "parsing"
    ],
    "license": "MIT",
    "main": "lib/lacona.js",
    "maintainers": [
        {
            "name": "brandonhorst"
        }
    ],
    "name": "lacona",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lacona/lacona.git"
    },
    "scripts": {
        "build": "babel --optional runtime --stage 0 src --out-dir lib",
        "clean": "rimraf lib tmp",
        "prepublish": "npm run clean && npm run build",
        "pretest": "babel --optional runtime --stage 0 test --out-dir tmp",
        "test": "mocha tmp",
        "validate": "npm run build && npm test"
    },
    "version": "0.39.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
