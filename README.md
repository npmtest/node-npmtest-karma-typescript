# npmtest-karma-typescript

#### test coverage for  [karma-typescript (v3.0.0)](https://github.com/monounity/karma-typescript#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-karma-typescript.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-karma-typescript) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-karma-typescript.svg)](https://travis-ci.org/npmtest/node-npmtest-karma-typescript)

#### Simplifying running unit tests with coverage for Typescript projects.

[![NPM](https://nodei.co/npm/karma-typescript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/karma-typescript)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-karma-typescript/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-typescript/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-karma-typescript/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-karma-typescript/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-karma-typescript/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-karma-typescript/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-karma-typescript/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-karma-typescript/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-karma-typescript/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-karma-typescript/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-karma-typescript/build/test-report.html](https://npmtest.github.io/node-npmtest-karma-typescript/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-karma-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-karma-typescript/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-karma-typescript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-karma-typescript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-typescript/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-karma-typescript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-karma-typescript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "monounity"
    },
    "bugs": {
        "url": "https://github.com/monounity/karma-typescript/issues"
    },
    "contributors": [
        {
            "name": "erikbarke"
        },
        {
            "name": "g00fy-"
        },
        {
            "name": "kubut"
        },
        {
            "name": "VilleSalonen"
        },
        {
            "name": "tokrsen"
        },
        {
            "name": "moshmage"
        },
        {
            "name": "fchiumeo"
        },
        {
            "name": "sir-marc"
        },
        {
            "name": "glennvorhes"
        }
    ],
    "dependencies": {
        "acorn": "^4.0.4",
        "amdefine": "1.0.0",
        "assert": "~1.3.0",
        "async": "^2.1.4",
        "base64-js": "^1.0.2",
        "browser-resolve": "^1.11.0",
        "browserify-zlib": "~0.1.2",
        "buffer": "^4.1.0",
        "console-browserify": "^1.1.0",
        "constants-browserify": "~1.0.0",
        "crypto-browserify": "^3.0.0",
        "diff": "^3.2.0",
        "domain-browser": "~1.1.0",
        "es6-promise": "^4.0.5",
        "events": "~1.1.0",
        "glob": "^7.1.1",
        "gulp-util": "3.0.7",
        "https-browserify": "~0.0.0",
        "ieee754": "^1.1.4",
        "isarray": "^1.0.0",
        "istanbul": "0.4.5",
        "karma-coverage": "^1.1.1",
        "lodash": "^4.17.4",
        "log4js": "^1.1.1",
        "magic-string": "^0.19.0",
        "minimatch": "^3.0.3",
        "os-browserify": "~0.1.1",
        "pad": "^1.1.0",
        "path-browserify": "~0.0.0",
        "process": "~0.11.0",
        "punycode": "^1.3.2",
        "querystring-es3": "~0.2.0",
        "readable-stream": "^2.0.2",
        "remap-istanbul": "^0.8.4",
        "source-map": ">=0.5.6",
        "stream-browserify": "^2.0.0",
        "stream-http": "^2.0.0",
        "string_decoder": "~0.10.0",
        "through2": "2.0.1",
        "timers-browserify": "^1.0.1",
        "tmp": "0.0.29",
        "tty-browserify": "~0.0.0",
        "url": "~0.11.0",
        "util": "~0.10.1",
        "vm-browserify": "~0.0.1"
    },
    "description": "Simplifying running unit tests with coverage for Typescript projects.",
    "devDependencies": {
        "@types/acorn": "^4.0.0",
        "@types/async": "^2.0.38",
        "@types/browser-resolve": "0.0.4",
        "@types/diff": "0.0.31",
        "@types/glob": "^5.0.30",
        "@types/istanbul": "^0.4.29",
        "@types/karma": "^0.13.33",
        "@types/lodash": "^4.14.59",
        "@types/minimatch": "^2.0.29",
        "@types/node": "^7.0.5",
        "@types/pad": "^1.0.0",
        "@types/tmp": "0.0.32",
        "cli-clear": "^1.0.4",
        "copy": "^0.3.0",
        "del": "^2.2.2",
        "eslint": "^3.4.0",
        "gulp": "^3.9.1",
        "gulp-util": "^3.0.7",
        "tslint": "^4.4.2",
        "tslint-eslint-rules": "^3.3.0",
        "typescript": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "517abd4fa2e36fdab4f191975226b58e1de5a76a",
        "tarball": "https://registry.npmjs.org/karma-typescript/-/karma-typescript-3.0.0.tgz"
    },
    "gitHead": "2b5f3a9f3ceb36aff97d3ea80ca42f134c1cf51b",
    "homepage": "https://github.com/monounity/karma-typescript#readme",
    "keywords": [
        "angularjs",
        "angular2",
        "browserify",
        "commonjs",
        "coverage",
        "docker",
        "istanbul",
        "jasmine",
        "karma",
        "karma plugin",
        "karma-coverage",
        "karma-plugin",
        "mocha",
        "react",
        "remap",
        "remap-istanbul",
        "transpile",
        "typescript",
        "unit test"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "erikbarke"
        },
        {
            "name": "monounity"
        }
    ],
    "name": "karma-typescript",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/monounity/karma-typescript.git"
    },
    "scripts": {
        "build": "tsc --rootDir ./src",
        "build:ci": "tsc --noEmit --rootDir ./src",
        "build:watch": "tsc -w --rootDir ./src",
        "lint": "eslint ./lib/*.js && tslint --project tsconfig.json",
        "test": "./ci/run.sh",
        "test:unix": "./ci/install.sh && ./ci/run.sh",
        "test:windows": ".\\ci\\install.bat & .\\ci\\run.bat"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
