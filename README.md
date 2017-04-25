# npmtest-gulp-useref

#### basic test coverage for  [gulp-useref (v3.1.2)](https://github.com/jonkemp/gulp-useref#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-useref.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-useref) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-useref.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-useref)

#### Parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets.

[![NPM](https://nodei.co/npm/gulp-useref.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-useref)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-useref/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-useref/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-useref/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-useref/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-useref/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gulp-useref/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gulp-useref/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-useref/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-useref/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-useref/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-useref/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-useref/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-useref/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-useref/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-useref/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-useref/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-useref/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-useref/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-useref/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-useref/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-useref/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-useref/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-useref/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Kemp",
        "url": "http://jonkemp.com/"
    },
    "bugs": {
        "url": "https://github.com/jonkemp/gulp-useref/issues"
    },
    "dependencies": {
        "event-stream": "^3.3.1",
        "glob": "^7.0.3",
        "gulp-concat": "^2.5.2",
        "gulp-if": "^2.0.0",
        "gulp-util": "^3.0.1",
        "is-relative-url": "1.0.0",
        "through2": "^2.0.1",
        "useref": "^1.2.0",
        "vinyl-fs": "^2.2.1"
    },
    "description": "Parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets.",
    "devDependencies": {
        "coveralls": "^2.11.4",
        "gulp": "^3.9.0",
        "gulp-eslint": "^3.0.1",
        "gulp-mocha": "^3.0.1",
        "gulp-rename": "^1.2.2",
        "mocha": "*",
        "mock-gulp-dest": "^0.1.1",
        "nyc": "^8.1.0",
        "should": "*"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "dec67024a96e685eeb9d9d8153c64a5d5c5e3cf6",
        "tarball": "https://registry.npmjs.org/gulp-useref/-/gulp-useref-3.1.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "1ce8e74945d0609409d08a9ead689fb178f1ed39",
    "homepage": "https://github.com/jonkemp/gulp-useref#readme",
    "keywords": [
        "gulpplugin",
        "html",
        "scripts",
        "css",
        "optimize",
        "concat"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonkemp"
        }
    ],
    "name": "gulp-useref",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonkemp/gulp-useref.git"
    },
    "scripts": {
        "coverage": "nyc npm test && nyc report",
        "coveralls": "nyc npm test && nyc report --reporter=text-lcov | coveralls",
        "lint": "gulp lint",
        "test": "mocha"
    },
    "version": "3.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
