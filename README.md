# npmtest-sort-by

#### basic test coverage for  [sort-by (v1.2.0)](https://github.com/kvnneff/sort-by#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sort-by.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sort-by) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sort-by.svg)](https://travis-ci.org/npmtest/node-npmtest-sort-by)

#### Sort objects by property names using native Array.sort()

[![NPM](https://nodei.co/npm/sort-by.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sort-by)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sort-by/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sort-by/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sort-by/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sort-by/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sort-by/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sort-by/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sort-by/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sort-by/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sort-by/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sort-by/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sort-by/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sort-by/build/test-report.html](https://npmtest.github.io/node-npmtest-sort-by/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sort-by/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sort-by/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sort-by/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sort-by/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sort-by/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sort-by/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sort-by/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sort-by/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin Neff"
    },
    "bugs": {
        "url": "https://github.com/kvnneff/sort-by/issues"
    },
    "dependencies": {
        "object-path": "0.6.0"
    },
    "description": "Sort objects by property names using native Array.sort()",
    "devDependencies": {
        "duo": "^0.9.6",
        "duo-test": "^0.3.13",
        "insist": "^0.2.3",
        "mocha": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "ed92bbff9fd2284b41f6503e38496607b225fe6f",
        "tarball": "https://registry.npmjs.org/sort-by/-/sort-by-1.2.0.tgz"
    },
    "gitHead": "04624e3598af8a2f03925a34b5c05e4ca22107e1",
    "homepage": "https://github.com/kvnneff/sort-by#readme",
    "keywords": [
        "array",
        "object",
        "sort"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kvnneff"
        }
    ],
    "name": "sort-by",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/kvnneff/sort-by.git"
    },
    "scripts": {
        "test": "make test"
    },
    "testling": {
        "harness": "mocha",
        "scripts": [
            "test/build.js"
        ],
        "preprocess": "make build-test",
        "browsers": [
            "ie/6.0..latest",
            "chrome/22.0..latest",
            "firefox/16.0..latest",
            "safari/latest",
            "opera/11.0..latest",
            "iphone/6.0",
            "ipad/6.0",
            "android-browser/latest"
        ]
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
