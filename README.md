# npmtest-passport-openidconnect

#### test coverage for  [passport-openidconnect (v0.0.2)](https://github.com/jaredhanson/passport-openidconnect#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-openidconnect.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-openidconnect) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-openidconnect.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-openidconnect)

#### OpenID Connect authentication strategy for Passport.

[![NPM](https://nodei.co/npm/passport-openidconnect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-openidconnect)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-openidconnect/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-openidconnect/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-openidconnect/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-openidconnect/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-openidconnect/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-openidconnect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-openidconnect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-openidconnect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-openidconnect/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-openidconnect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/passport-openidconnect/issues"
    },
    "dependencies": {
        "oauth": "0.9.x",
        "passport-strategy": "1.x.x",
        "request": "^2.75.0",
        "webfinger": "0.4.x"
    },
    "description": "OpenID Connect authentication strategy for Passport.",
    "devDependencies": {
        "chai": "2.x.x",
        "chai-passport-strategy": "1.x.x",
        "jsonwebtoken": "^7.1.9",
        "make-node": "0.3.x",
        "mocha": "2.x.x",
        "proxyquire": "^1.7.10",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "e488f8bdb386c9a9fd39c91d5ab8c880156e8153",
        "tarball": "https://registry.npmjs.org/passport-openidconnect/-/passport-openidconnect-0.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "ac1c0257f02353f818be33c0602cca5883d97235",
    "homepage": "https://github.com/jaredhanson/passport-openidconnect#readme",
    "keywords": [
        "passport",
        "openid",
        "openidconnect",
        "auth",
        "authn",
        "authentication",
        "identity"
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
    "name": "passport-openidconnect",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/passport-openidconnect.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js"
    },
    "version": "0.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
