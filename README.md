# npmtest-chimp

#### basic test coverage for  [chimp (v0.48.0)](https://github.com/xolvio/chimp#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-chimp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-chimp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-chimp.svg)](https://travis-ci.org/npmtest/node-npmtest-chimp)

#### Develop acceptance tests & end-to-end tests with realtime feedback.

[![NPM](https://nodei.co/npm/chimp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chimp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-chimp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-chimp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-chimp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-chimp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-chimp/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-chimp/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-chimp/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-chimp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-chimp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-chimp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-chimp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-chimp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-chimp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-chimp/build/test-report.html](https://npmtest.github.io/node-npmtest-chimp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-chimp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-chimp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-chimp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chimp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chimp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chimp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-chimp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-chimp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sam Hatoum",
        "url": "http://xolv.io"
    },
    "bin": {
        "chimp": "./bin/chimp.js"
    },
    "bugs": {
        "url": "https://github.com/xolvio/chimp/issues"
    },
    "bundleDependencies": [
        "cucumber"
    ],
    "dependencies": {
        "async": "~0.9.0",
        "babel-core": "^6.4.5",
        "babel-plugin-transform-runtime": "6.x.x",
        "babel-polyfill": "^6.3.14",
        "babel-preset-es2015": "6.x.x",
        "babel-preset-stage-2": "6.x.x",
        "babel-register": "^6.4.3",
        "babel-runtime": "6.x.x",
        "bluebird": "^3.4.7",
        "chai": "~3.5.0",
        "chai-as-promised": "^6.0.0",
        "child-process-debug": "0.0.7",
        "chokidar": "~1.6.0",
        "chromedriver": "^2.27.2",
        "colors": "1.1.2",
        "commander": "^2.9.0",
        "cucumber": "github:xolvio/cucumber-js#v1.3.0-chimp.3",
        "deep-extend": "^0.4.1",
        "exit": "^0.1.2",
        "fibers": "^1.0.14",
        "freeport": "~1.0.5",
        "fs-extra": "^1.0.0",
        "glob": "github:lucetius/node-glob#chimp",
        "hapi": "8.8.0",
        "jasmine": "^2.4.1",
        "loglevel": "~1.4.0",
        "minimist": "~1.2.0",
        "mocha": "^3.2.0",
        "phantomjs-prebuilt": "2.1.13",
        "progress": "^1.1.8",
        "request": "^2.79.0",
        "requestretry": "1.5.0",
        "saucelabs": "^1.3.0",
        "selenium-standalone": "^5.7.1",
        "underscore": "~1.8.3",
        "xolvio-ddp": "^0.12.0",
        "xolvio-jasmine-expect": "^1.0.0",
        "xolvio-sync-webdriverio": "^8.0.0"
    },
    "description": "Develop acceptance tests & end-to-end tests with realtime feedback.",
    "devDependencies": {
        "babel-cli": "6.x.x",
        "babel-jest": "^6.0.1",
        "eslint": "^3.12.2",
        "eslint-config-airbnb": "^13.0.0",
        "eslint-plugin-babel": "^4.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^6.8.0",
        "git-release-notes": "0.0.2",
        "jest-cli": "github:sanjo/jest#7c71094",
        "npm-watch": "^0.1.6",
        "quibble": "^0.4.0",
        "shelljs": "^0.7.5",
        "testdouble": "^1.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "67673d24c23044e13aa2f852547309932f414cdb",
        "tarball": "https://registry.npmjs.org/chimp/-/chimp-0.48.0.tgz"
    },
    "gitHead": "82b6ced354662f4f1547feef1caf27bda1c614a7",
    "homepage": "https://github.com/xolvio/chimp#readme",
    "jest": {
        "testRunner": "<rootDir>/node_modules/jest-cli/src/testRunners/jasmine/jasmine2.js",
        "scriptPreprocessor": "<rootDir>/node_modules/babel-jest",
        "moduleFileExtensions": [
            "js",
            "json",
            "node"
        ],
        "unmockedModulePathPatterns": [
            "core-js/.*",
            "babel-runtime/.*"
        ]
    },
    "keywords": [
        "simian",
        "meteor",
        "bdd",
        "atdd",
        "cucumber",
        "webdriverio",
        "selenium",
        "phantom",
        "testing",
        "saucelabs"
    ],
    "license": "MIT",
    "main": "dist/lib/chimp.js",
    "maintainers": [
        {
            "name": "xolvio"
        },
        {
            "name": "sanjo"
        },
        {
            "name": "samhatoum"
        }
    ],
    "mocha": {
        "files": [
            "src/**/*.js",
            "!src/__mocks__/**/*",
            "!src/__tests__/**/*",
            "!src/**/*-spec.js"
        ],
        "tests": [
            "src/lib/**/*-spec.js"
        ]
    },
    "name": "chimp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/xolvio/chimp.git"
    },
    "scripts": {
        "lint": "eslint ./src",
        "lintfix": "eslint ./src --fix",
        "prepublish": "node ./scripts/prepublish.js",
        "publish-major": "./scripts/release.sh major",
        "publish-minor": "./scripts/release.sh minor",
        "publish-patch": "./scripts/release.sh patch",
        "start": "node ./scripts/run.js",
        "test": "npm run lint && npm run testonly",
        "testonly": "npm run testunit && npm run prepublish && node ./scripts/run-tests.js",
        "testunit": "mocha --opts ./mocha.opts \"'node -e \"console.log(require('./package.json').mocha.tests.join(' '))\"'\"",
        "watch": "npm-watch"
    },
    "version": "0.48.0",
    "watch": {
        "prepublish": "src/{lib,bin}/**/*.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
