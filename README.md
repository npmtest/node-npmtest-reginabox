# npmtest-reginabox

#### basic test coverage for  [reginabox (v1.0.1)](https://github.com/yahoo/reginabox)  [![npm package](https://img.shields.io/npm/v/npmtest-reginabox.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-reginabox) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-reginabox.svg)](https://travis-ci.org/npmtest/node-npmtest-reginabox)

#### instant npm mirror

[![NPM](https://nodei.co/npm/reginabox.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reginabox)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-reginabox/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-reginabox/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-reginabox/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-reginabox/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-reginabox/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-reginabox/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-reginabox/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-reginabox/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-reginabox/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-reginabox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-reginabox/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-reginabox/build/test-report.html](https://npmtest.github.io/node-npmtest-reginabox/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-reginabox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-reginabox/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-reginabox/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reginabox/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reginabox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reginabox/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-reginabox/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-reginabox/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "reginabox",
    "version": "1.0.1",
    "description": "instant npm mirror",
    "main": "index.js",
    "bin": "index.js",
    "repository": {
        "type": "git",
        "url": "git@github.com:yahoo/reginabox.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "keywords": [
        "npm",
        "mirror",
        "registry",
        "registry-static"
    ],
    "author": "bengl",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/yahoo/reginabox/issues"
    },
    "homepage": "https://github.com/yahoo/reginabox",
    "dependencies": {
        "davlog": "0.0.2",
        "express": "^4.12.3",
        "lru-cache": "^2.5.0",
        "mdns": "^2.2.8",
        "registry-static": "^0.1.11",
        "st": "^1.2.0"
    },
    "devDependencies": {
        "mocha": "^2.2.1",
        "mockery": "^1.4.0",
        "ncp": "^2.0.0",
        "nock": "^1.2.1",
        "request": "^2.54.0",
        "rimraf": "^2.3.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
