# npmtest-gulp-develop-server

#### basic test coverage for  [gulp-develop-server (v0.5.2)](https://github.com/narirou/gulp-develop-server#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-develop-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-develop-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-develop-server.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-develop-server)

#### run node.js server and automatically restart for your development.

[![NPM](https://nodei.co/npm/gulp-develop-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-develop-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-develop-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gulp-develop-server/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-develop-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-develop-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-develop-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-develop-server/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-develop-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-develop-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-develop-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-develop-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-develop-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "auther": "narirou <narirou.github@gmail.com>",
    "bugs": {
        "url": "https://github.com/narirou/gulp-develop-server/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.3",
        "lodash": "^4.13.1"
    },
    "description": "run node.js server and automatically restart for your development.",
    "devDependencies": {
        "express": "^4.4.5",
        "istanbul": "^0.4.0",
        "mocha": "^2.1.0",
        "should": "^8.4.0",
        "sinon": "^1.12.2",
        "supertest": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "20d1c9039e93f6a7c3c3cc84d557a9052c230cf4",
        "tarball": "https://registry.npmjs.org/gulp-develop-server/-/gulp-develop-server-0.5.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "3f8eb437a50f6ef0553388006609d5fd8abd7398",
    "homepage": "https://github.com/narirou/gulp-develop-server#readme",
    "keywords": [
        "gulpplugin",
        "gulp",
        "server",
        "restart",
        "express"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "narirou"
        }
    ],
    "name": "gulp-develop-server",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/narirou/gulp-develop-server.git"
    },
    "scripts": {
        "test": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter spec --timeout 3000 ./test/test"
    },
    "version": "0.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
