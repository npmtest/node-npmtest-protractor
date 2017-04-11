# test coverage for  [protractor (v5.1.1)](https://github.com/angular/protractor)  [![npm package](https://img.shields.io/npm/v/npmtest-protractor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-protractor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-protractor.svg)](https://travis-ci.org/npmtest/node-npmtest-protractor)
#### Webdriver E2E test wrapper for Angular.

[![NPM](https://nodei.co/npm/protractor.png?downloads=true)](https://www.npmjs.com/package/protractor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-protractor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-protractor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-protractor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-protractor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-protractor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-protractor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-protractor/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-protractor/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-protractor/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-protractor/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-protractor%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-protractor/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-protractor/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-protractor%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-protractor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-protractor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-protractor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julie Ralph",
        "email": "ju.ralph@gmail.com"
    },
    "bin": {
        "protractor": "bin/protractor",
        "webdriver-manager": "bin/webdriver-manager"
    },
    "bugs": {
        "url": "https://github.com/angular/protractor/issues"
    },
    "dependencies": {
        "@types/node": "^6.0.46",
        "@types/q": "^0.0.32",
        "@types/selenium-webdriver": "~2.53.39",
        "blocking-proxy": "0.0.5",
        "chalk": "^1.1.3",
        "glob": "^7.0.3",
        "jasmine": "^2.5.3",
        "jasminewd2": "^2.0.0",
        "optimist": "~0.6.0",
        "q": "1.4.1",
        "saucelabs": "~1.3.0",
        "selenium-webdriver": "3.0.1",
        "source-map-support": "~0.4.0",
        "webdriver-js-extender": "^1.0.0",
        "webdriver-manager": "^12.0.1"
    },
    "description": "Webdriver E2E test wrapper for Angular.",
    "devDependencies": {
        "@types/chalk": "^0.4.28",
        "@types/glob": "^5.0.29",
        "@types/jasmine": "^2.5.38",
        "@types/jasminewd2": "^2.0.0",
        "@types/minimatch": "^2.0.28",
        "@types/minimist": "^1.1.28",
        "@types/optimist": "^0.0.29",
        "body-parser": "~1.15.2",
        "chai": "~3.5.0",
        "chai-as-promised": "~5.3.0",
        "clang-format": "^1.0.34",
        "expect.js": "~0.3.1",
        "express": "~4.14.0",
        "gulp": "^3.9.1",
        "gulp-clang-format": "^1.0.23",
        "gulp-tslint": "^7.0.1",
        "jshint": "^2.9.2",
        "lodash": "^4.5.1",
        "marked": "^0.3.3",
        "mocha": "2.5.3",
        "rimraf": "~2.5.3",
        "run-sequence": "^1.1.5",
        "semver": "^5.3.0",
        "tslint": "~4.3.0",
        "tslint-eslint-rules": "^3.2.0",
        "typescript": "~2.0.0",
        "vrsource-tslint-rules": "^4.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "10c4e336571b28875b8acc3ae3e4e1e40ef7e986",
        "tarball": "https://registry.npmjs.org/protractor/-/protractor-5.1.1.tgz"
    },
    "engines": {
        "node": ">=6.9.x"
    },
    "gitHead": "ba544224f6cfe07b8bf3a75772835d72f397cabc",
    "homepage": "https://github.com/angular/protractor",
    "keywords": [
        "angular",
        "test",
        "testing",
        "webdriver",
        "webdriverjs",
        "selenium"
    ],
    "license": "MIT",
    "main": "built/index.js",
    "maintainers": [
        {
            "name": "juliemr",
            "email": "ju.ralph@gmail.com"
        },
        {
            "name": "angularcore",
            "email": "angular-core+npm@google.com"
        }
    ],
    "name": "protractor",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/angular/protractor.git"
    },
    "scripts": {
        "format": "gulp format",
        "install_testapp": "cd testapp && npm install",
        "prepublish": "gulp prepublish",
        "pretest": "gulp pretest",
        "start": "cd testapp && npm start",
        "test": "node scripts/test.js",
        "website": "cd website && npm start"
    },
    "typings": "built/index.d.ts",
    "version": "5.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
