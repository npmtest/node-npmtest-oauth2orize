# npmtest-oauth2orize

#### basic test coverage for  [oauth2orize (v1.8.0)](https://github.com/jaredhanson/oauth2orize#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-oauth2orize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-oauth2orize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-oauth2orize.svg)](https://travis-ci.org/npmtest/node-npmtest-oauth2orize)

#### OAuth 2.0 authorization server toolkit for Node.js.

[![NPM](https://nodei.co/npm/oauth2orize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/oauth2orize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-oauth2orize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-oauth2orize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-oauth2orize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-oauth2orize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-oauth2orize/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-oauth2orize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-oauth2orize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-oauth2orize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-oauth2orize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-oauth2orize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-oauth2orize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-oauth2orize/build/test-report.html](https://npmtest.github.io/node-npmtest-oauth2orize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-oauth2orize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-oauth2orize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-oauth2orize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-oauth2orize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-oauth2orize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-oauth2orize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-oauth2orize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-oauth2orize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/oauth2orize/issues"
    },
    "dependencies": {
        "debug": "2.x.x",
        "uid2": "0.0.x",
        "utils-merge": "1.x.x"
    },
    "description": "OAuth 2.0 authorization server toolkit for Node.js.",
    "devDependencies": {
        "chai": "2.x.x",
        "chai-connect-middleware": "0.3.x",
        "chai-oauth2orize-grant": "0.3.x",
        "make-node": "0.3.x",
        "mocha": "2.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "f2ddc0115d635d0480746249c00f0ea1a9c51ba8",
        "tarball": "https://registry.npmjs.org/oauth2orize/-/oauth2orize-1.8.0.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "58cbc13f0097294cf245e9ed85c29e55e979cac5",
    "homepage": "https://github.com/jaredhanson/oauth2orize#readme",
    "keywords": [
        "oauth",
        "oauth2",
        "auth",
        "authz",
        "authorization",
        "connect",
        "express",
        "passport",
        "middleware"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://opensource.org/licenses/MIT"
        }
    ],
    "main": "./lib",
    "maintainers": [
        {
            "name": "jaredhanson"
        }
    ],
    "name": "oauth2orize",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/oauth2orize.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js"
    },
    "version": "1.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
