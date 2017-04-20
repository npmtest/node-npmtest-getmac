# npmtest-getmac

#### basic test coverage for  [getmac (v1.2.1)](https://github.com/bevry/getmac)  [![npm package](https://img.shields.io/npm/v/npmtest-getmac.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-getmac) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-getmac.svg)](https://travis-ci.org/npmtest/node-npmtest-getmac)

#### Get the mac address of the current machine you are on

[![NPM](https://nodei.co/npm/getmac.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/getmac)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-getmac/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-getmac/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-getmac/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-getmac/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-getmac/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-getmac/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-getmac/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-getmac/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-getmac/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-getmac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-getmac/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-getmac/build/test-report.html](https://npmtest.github.io/node-npmtest-getmac/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-getmac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-getmac/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-getmac/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-getmac/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-getmac/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-getmac/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-getmac/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-getmac/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "2013+ Bevry Pty Ltd",
        "url": "http://bevry.me"
    },
    "badges": {
        "list": [
            "travisci",
            "npmversion",
            "npmdownloads",
            "daviddm",
            "daviddmdev",
            "---",
            "slackin",
            "patreon",
            "gratipay",
            "flattr",
            "paypal",
            "bitcoin",
            "wishlist"
        ],
        "config": {
            "patreonUsername": "bevry",
            "gratipayUsername": "bevry",
            "flattrUsername": "balupton",
            "paypalURL": "https://bevry.me/paypal",
            "bitcoinURL": "https://bevry.me/bitcoin",
            "wishlistURL": "https://bevry.me/wishlist",
            "slackinURL": "https://slack.bevry.me"
        }
    },
    "bin": {
        "getmac-node": "bin/getmac-node"
    },
    "browser": "es5/lib/getmac.js",
    "bugs": {
        "url": "https://github.com/bevry/getmac/issues"
    },
    "contributors": [
        {
            "name": "Benjamin Lupton",
            "url": "https://balupton.com"
        },
        {
            "name": "Stephen Brown II",
            "url": "https://github.com/StephenBrown2"
        }
    ],
    "dependencies": {
        "extract-opts": "^3.2.0"
    },
    "description": "Get the mac address of the current machine you are on",
    "devDependencies": {
        "chai": "^3.5.0",
        "coffee-script": "^1.10.0",
        "coffeelint": "^1.15.7",
        "joe": "^1.6.0",
        "joe-reporter-console": "^1.2.1",
        "projectz": "^1.1.5"
    },
    "directories": {},
    "dist": {
        "shasum": "0d095fd0627850043eac1dcfa0b120bbdc1426d1",
        "tarball": "https://registry.npmjs.org/getmac/-/getmac-1.2.1.tgz"
    },
    "editions": [
        {
            "description": "Source + CoffeeScript + Require",
            "entry": "src/lib/getmac.coffee",
            "directory": "src",
            "syntaxes": [
                "coffeescript",
                "require"
            ]
        },
        {
            "description": "CoffeeScript Compiled JavaScript + ES5 + Require",
            "entry": "es5/lib/getmac.js",
            "directory": "es5",
            "syntaxes": [
                "javascript",
                "es5",
                "require"
            ]
        }
    ],
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "49b1832c88b2c0edbdc7a172b6bd14dcfc45e305",
    "homepage": "https://github.com/bevry/getmac",
    "keywords": [
        "mac",
        "mac-address",
        "ifconfig",
        "ipconfig",
        "getmac"
    ],
    "license": "MIT",
    "main": "es5/lib/getmac.js",
    "maintainers": [
        {
            "name": "balupton"
        },
        {
            "name": "stephenbrown2"
        }
    ],
    "name": "getmac",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bevry/getmac.git"
    },
    "scripts": {
        "clean": "rm -Rf ./docs ./es5",
        "compile": "npm run compile:coffeescript",
        "compile:coffeescript": "coffee -bco ./es5 ./src",
        "meta": "npm run meta:projectz",
        "meta:projectz": "projectz compile",
        "prepare": "npm run compile && npm run test && npm run meta",
        "pretest": "npm run test:coffeelint",
        "release": "npm run prepare && npm run release:publish && npm run release:tag && npm run release:push",
        "release:publish": "npm publish",
        "release:push": "git push origin master && git push origin --tags",
        "release:tag": "git tag v$npm_package_version -a",
        "setup": "npm install",
        "test": "node --harmony ./es5/test/everything-test.js",
        "test:coffeelint": "coffeelint ./src"
    },
    "version": "1.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
