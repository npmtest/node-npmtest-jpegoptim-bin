# npmtest-jpegoptim-bin

#### basic test coverage for  [jpegoptim-bin (v3.0.0)](https://github.com/imagemin/jpegoptim-bin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jpegoptim-bin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jpegoptim-bin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jpegoptim-bin.svg)](https://travis-ci.org/npmtest/node-npmtest-jpegoptim-bin)

#### jpegoptim wrapper that makes it seamlessly available as a local dependency

[![NPM](https://nodei.co/npm/jpegoptim-bin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jpegoptim-bin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jpegoptim-bin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jpegoptim-bin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jpegoptim-bin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/test-report.html](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jpegoptim-bin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jpegoptim-bin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "1000ch",
        "url": "http://github.com/1000ch"
    },
    "bin": {
        "jpegoptim": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/imagemin/jpegoptim-bin/issues"
    },
    "dependencies": {
        "bin-build": "^2.0.0",
        "bin-wrapper": "^3.0.0",
        "logalot": "^2.0.0"
    },
    "description": "jpegoptim wrapper that makes it seamlessly available as a local dependency",
    "devDependencies": {
        "bin-check": "^1.0.0",
        "compare-size": "^1.0.1",
        "mkdirp": "^0.5.0",
        "mocha": "^2.2.4",
        "rimraf": "^2.3.2",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "9f7a05d83b302bd19913decf339a9dae1bda0c2b",
        "tarball": "https://registry.npmjs.org/jpegoptim-bin/-/jpegoptim-bin-3.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "cli.js",
        "index.js",
        "lib"
    ],
    "gitHead": "6486ac51ad25c596d2fd930c6fc577b6c2c16fdc",
    "homepage": "https://github.com/imagemin/jpegoptim-bin#readme",
    "keywords": [
        "compress",
        "image",
        "img",
        "jpeg",
        "jpg",
        "minify",
        "optimize"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "1000ch"
        },
        {
            "name": "kevva"
        },
        {
            "name": "shinnn"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "jpegoptim-bin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/imagemin/jpegoptim-bin.git"
    },
    "scripts": {
        "postinstall": "node lib/install.js",
        "test": "xo && mocha --timeout 50000"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
