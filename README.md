# npmtest-express-csv

#### basic test coverage for  express-csv (v0.6.0)  [![npm package](https://img.shields.io/npm/v/npmtest-express-csv.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-csv) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-csv.svg)](https://travis-ci.org/npmtest/node-npmtest-express-csv)

#### express-csv provides response csv easily to express.

[![NPM](https://nodei.co/npm/express-csv.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-csv)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-csv/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-csv/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-csv/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-csv/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-csv/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-csv/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-csv/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-csv/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-csv/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-csv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-csv/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-csv/build/test-report.html](https://npmtest.github.io/node-npmtest-express-csv/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-csv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-csv/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-csv/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-csv/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-csv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-csv/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-csv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-csv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-csv",
    "description": "express-csv provides response csv easily to express.",
    "version": "0.6.0",
    "author": "Seiya Konno <nulltask@gmail.com>",
    "contributors": [
        {
            "name": "Matthew Blackshaw",
            "web": "http://mattblackshaw.com"
        },
        {
            "name": "Craig McDonald",
            "web": "http://thrackle.com"
        }
    ],
    "devDependencies": {
        "mocha": "*",
        "should": "*",
        "superagent": "*",
        "express": "2"
    },
    "keywords": [
        "express",
        "csv"
    ],
    "repository": "git://github.com/nulltask/express-csv.git",
    "main": "index",
    "engines": {
        "node": "0.6 || 0.8 || 0.10"
    },
    "scripts": {
        "test": "mocha",
        "prepublish": "make test"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
