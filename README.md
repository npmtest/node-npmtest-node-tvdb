# npmtest-node-tvdb

#### basic test coverage for  [node-tvdb (v3.1.1)](https://github.com/edwellbrook/node-tvdb)  [![npm package](https://img.shields.io/npm/v/npmtest-node-tvdb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-tvdb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-tvdb.svg)](https://travis-ci.org/npmtest/node-npmtest-node-tvdb)

#### Node.js library for accessing TheTVDB's API

[![NPM](https://nodei.co/npm/node-tvdb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-tvdb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-tvdb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-tvdb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-tvdb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-tvdb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-tvdb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-tvdb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-tvdb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-tvdb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-tvdb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-tvdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-tvdb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-tvdb/build/test-report.html](https://npmtest.github.io/node-npmtest-node-tvdb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-tvdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-tvdb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-tvdb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-tvdb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-tvdb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-tvdb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-tvdb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-tvdb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Edward Wellbrook"
    },
    "bugs": {
        "url": "https://github.com/edwellbrook/node-tvdb/issues"
    },
    "dependencies": {
        "lodash": "^4.17.3",
        "node-fetch": "^1.6.3"
    },
    "description": "Node.js library for accessing TheTVDB's API",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "eslint": "latest",
        "eslint-plugin-mocha": "^4.8.0",
        "jsdoc": "^3.4.3",
        "minami": "github:edwellbrook/minami",
        "mocha": "^3.2.0",
        "nock": "^9.0.9",
        "sinon": "^1.17.7",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3750c1dbcbccd78b55075e575d9b72993734341c",
        "tarball": "https://registry.npmjs.org/node-tvdb/-/node-tvdb-3.1.1.tgz"
    },
    "engines": {
        "node": ">=4.3.2"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "149c3e41ad101e7ab39cd02aca017b838bc4587a",
    "homepage": "https://github.com/edwellbrook/node-tvdb",
    "keywords": [
        "tv",
        "tvdb",
        "thetvdb",
        "api",
        "wrapper"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "edwellbrook"
        }
    ],
    "name": "node-tvdb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/edwellbrook/node-tvdb.git"
    },
    "scripts": {
        "eslint": "eslint .",
        "generate-docs": "rm -rf ./docs && jsdoc -c .jsdoc.json",
        "test": "mocha test && eslint ."
    },
    "version": "3.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
