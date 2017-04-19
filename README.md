# npmtest-css

#### basic test coverage for  [css (v2.2.1)](https://github.com/reworkcss/css#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-css.svg)](https://travis-ci.org/npmtest/node-npmtest-css)

#### CSS parser / stringifier

[![NPM](https://nodei.co/npm/css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-css/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-css/build/test-report.html](https://npmtest.github.io/node-npmtest-css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "bugs": {
        "url": "https://github.com/reworkcss/css/issues"
    },
    "dependencies": {
        "inherits": "^2.0.1",
        "source-map": "^0.1.38",
        "source-map-resolve": "^0.3.0",
        "urix": "^0.1.0"
    },
    "description": "CSS parser / stringifier",
    "devDependencies": {
        "bytes": "^1.0.0",
        "matcha": "^0.5.0",
        "mocha": "^1.21.3",
        "should": "^4.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "73a4c81de85db664d4ee674f7d47085e3b2d55dc",
        "tarball": "https://registry.npmjs.org/css/-/css-2.2.1.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "e38b6f1cc03aa36ff161a3da96b5c7510bd41ca7",
    "homepage": "https://github.com/reworkcss/css#readme",
    "keywords": [
        "css",
        "parser",
        "stringifier",
        "stylesheet"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "jonathanong"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "conradz"
        },
        {
            "name": "necolas"
        },
        {
            "name": "anthonyshort"
        },
        {
            "name": "ianstormtaylor"
        },
        {
            "name": "moox"
        },
        {
            "name": "clintwood"
        },
        {
            "name": "lydell"
        },
        {
            "name": "slexaxton"
        }
    ],
    "name": "css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reworkcss/css.git"
    },
    "scripts": {
        "benchmark": "matcha",
        "test": "mocha --require should --reporter spec --bail test/*.js"
    },
    "version": "2.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
