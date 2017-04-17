# test coverage for  [connect-mongo (v1.3.2)](https://github.com/kcbanner/connect-mongo#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-connect-mongo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-connect-mongo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-connect-mongo.svg)](https://travis-ci.org/npmtest/node-npmtest-connect-mongo)
#### MongoDB session store for Express and Connect

[![NPM](https://nodei.co/npm/connect-mongo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/connect-mongo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-connect-mongo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-mongo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-connect-mongo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-connect-mongo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-connect-mongo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-connect-mongo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-connect-mongo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-connect-mongo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-connect-mongo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-connect-mongo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-connect-mongo/build/test-report.html](https://npmtest.github.io/node-npmtest-connect-mongo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-connect-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-connect-mongo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-connect-mongo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-connect-mongo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect-mongo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-connect-mongo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-connect-mongo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/kcbanner/connect-mongo/issues"
    },
    "contributors": [
        {
            "name": "Casey Banner"
        },
        {
            "name": "Jerome Desboeufs"
        }
    ],
    "dependencies": {
        "bluebird": "^3.0",
        "mongodb": ">= 1.2.0 <3.0.0"
    },
    "description": "MongoDB session store for Express and Connect",
    "devDependencies": {
        "babel-cli": "^6.3.17",
        "babel-plugin-transform-es2015-arrow-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoping": "^6.3.13",
        "babel-plugin-transform-es2015-classes": "^6.3.15",
        "babel-plugin-transform-es2015-object-super": "^6.3.13",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-register": "^6.3.13",
        "eslint": "^3.1.1",
        "expect.js": "^0.3.1",
        "express-session": ">= 1.0.0",
        "istanbul": "^0.4.1",
        "mocha": "^2.3.4",
        "mongoose": ">= 2.6.0 < 5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7cbf58dfff26760e5e00e017d0a85b4bc90b9d37",
        "tarball": "https://registry.npmjs.org/connect-mongo/-/connect-mongo-1.3.2.tgz"
    },
    "gitHead": "f4c8fa5d04777c0017f5123a10b71577de248d45",
    "homepage": "https://github.com/kcbanner/connect-mongo#readme",
    "keywords": [
        "connect",
        "mongo",
        "mongodb",
        "session",
        "express"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kcbanner"
        },
        {
            "name": "jdesboeufs"
        }
    ],
    "name": "connect-mongo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kcbanner/connect-mongo.git"
    },
    "scripts": {
        "cover": "istanbul cover -x 'src-es5/**' _mocha",
        "lint": "eslint src test",
        "prepublish": "npm run transpile",
        "test": "npm run lint && npm run transpile && npm run cover",
        "test-es5": "npm run transpile && npm run test-unit-es5",
        "test-unit": "mocha",
        "test-unit-es5": "mocha --compilers js:babel-register",
        "transpile": "babel src --out-dir src-es5"
    },
    "version": "1.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
