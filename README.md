# npmtest-es6-map

#### basic test-coverage for  [es6-map (v0.1.5)](https://github.com/medikoo/es6-map#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-es6-map.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-es6-map) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-es6-map.svg)](https://travis-ci.org/npmtest/node-npmtest-es6-map)

#### ECMAScript6 Map polyfill

[![NPM](https://nodei.co/npm/es6-map.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/es6-map)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-es6-map/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-map/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-es6-map/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-es6-map/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-es6-map/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-es6-map/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-es6-map/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-es6-map/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-es6-map/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-map/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-es6-map/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-es6-map/build/test-report.html](https://npmtest.github.io/node-npmtest-es6-map/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-es6-map/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-es6-map/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-es6-map/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-es6-map/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-es6-map/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-es6-map/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-es6-map/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-es6-map/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mariusz Nowak",
        "url": "http://www.medikoo.com/"
    },
    "bugs": {
        "url": "https://github.com/medikoo/es6-map/issues"
    },
    "dependencies": {
        "d": "1",
        "es5-ext": "~0.10.14",
        "es6-iterator": "~2.0.1",
        "es6-set": "~0.1.5",
        "es6-symbol": "~3.1.1",
        "event-emitter": "~0.3.5"
    },
    "description": "ECMAScript6 Map polyfill",
    "devDependencies": {
        "tad": "~0.2.7",
        "xlint": "~0.2.2",
        "xlint-jslint-medikoo": "~0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "9136e0503dcc06a301690f0bb14ff4e364e949f0",
        "tarball": "https://registry.npmjs.org/es6-map/-/es6-map-0.1.5.tgz"
    },
    "gitHead": "901fee71166dd5bc4b515b619521ae403a95472e",
    "homepage": "https://github.com/medikoo/es6-map#readme",
    "keywords": [
        "collection",
        "es6",
        "shim",
        "harmony",
        "list",
        "hash",
        "map",
        "polyfill",
        "ponyfill",
        "ecmascript"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "medikoo"
        }
    ],
    "name": "es6-map",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/medikoo/es6-map.git"
    },
    "scripts": {
        "lint": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --no-cache --no-stream",
        "lint-console": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --watch",
        "test": "node ./node_modules/tad/bin/tad"
    },
    "version": "0.1.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
