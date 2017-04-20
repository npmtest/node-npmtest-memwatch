# npmtest-memwatch

#### basic test coverage for  memwatch (v0.2.2)  [![npm package](https://img.shields.io/npm/v/npmtest-memwatch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-memwatch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-memwatch.svg)](https://travis-ci.org/npmtest/node-npmtest-memwatch)

#### Keep an eye on your memory usage, and discover and isolate leaks.

[![NPM](https://nodei.co/npm/memwatch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/memwatch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-memwatch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-memwatch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-memwatch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-memwatch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-memwatch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-memwatch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-memwatch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-memwatch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-memwatch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-memwatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-memwatch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-memwatch/build/test-report.html](https://npmtest.github.io/node-npmtest-memwatch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-memwatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-memwatch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-memwatch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-memwatch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-memwatch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-memwatch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-memwatch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-memwatch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "memwatch",
    "description": "Keep an eye on your memory usage, and discover and isolate leaks.",
    "version": "0.2.2",
    "author": "Lloyd Hilaiel (http://lloyd.io)",
    "engines": {
        "node": ">= 0.6.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/lloyd/node-memwatch.git"
    },
    "main": "include.js",
    "licenses": [
        {
            "type": "wtfpl"
        }
    ],
    "bugs": {
        "url": "https://github.com/lloyd/node-memwatch/issues"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "mocha tests"
    },
    "devDependencies": {
        "mocha": "1.2.2",
        "should": "0.6.3",
        "node-gyp": "0.5.7"
    },
    "contributors": [
        "Jed Parsons (@jedp)",
        "Jeff Haynie (@jhaynie)",
        "Justin Matthews (@jmatthewsr-ms)"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
