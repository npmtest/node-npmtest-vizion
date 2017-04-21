# npmtest-vizion

#### basic test coverage for  vizion (v0.2.13)  [![npm package](https://img.shields.io/npm/v/npmtest-vizion.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vizion) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vizion.svg)](https://travis-ci.org/npmtest/node-npmtest-vizion)

#### Git/Subversion/Mercurial repository metadata parser

[![NPM](https://nodei.co/npm/vizion.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vizion)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vizion/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vizion/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vizion/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vizion/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vizion/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vizion/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vizion/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vizion/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vizion/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vizion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vizion/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vizion/build/test-report.html](https://npmtest.github.io/node-npmtest-vizion/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vizion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vizion/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vizion/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vizion/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vizion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vizion/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vizion/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vizion/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "vizion",
    "version": "0.2.13",
    "engines": {
        "node": ">=0.10"
    },
    "author": {
        "name": "Joni Shkurti"
    },
    "keywords": [
        "git",
        "svn",
        "hg",
        "subversion",
        "mercurial",
        "repository",
        "parser",
        "versioning",
        "revision"
    ],
    "description": "Git/Subversion/Mercurial repository metadata parser",
    "repository": {
        "type": "git",
        "url": "https://github.com/keymetrics/vizion"
    },
    "main": "index.js",
    "scripts": {
        "cover": "node_modules/.bin/istanbul cover --report html node_modules/.bin/_mocha -- -R spec test/*",
        "test": "node_modules/.bin/_mocha --require test/support/env --reporter spec --bail --check-leaks test/"
    },
    "dependencies": {
        "async": "1.5"
    },
    "devDependencies": {
        "mocha": "2.0.0",
        "should": "*",
        "shelljs": "0.6.0",
        "istanbul": "*"
    },
    "bugs": {
        "url": "https://github.com/keymetrics/vizion/issues"
    },
    "license": "Apache-2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
