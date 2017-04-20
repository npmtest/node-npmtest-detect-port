# npmtest-detect-port

#### basic test coverage for  [detect-port (v1.1.1)](https://github.com/node-modules/detect-port)  [![npm package](https://img.shields.io/npm/v/npmtest-detect-port.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-detect-port) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-detect-port.svg)](https://travis-ci.org/npmtest/node-npmtest-detect-port)

#### detect available port

[![NPM](https://nodei.co/npm/detect-port.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/detect-port)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-detect-port/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-detect-port/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-detect-port/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-detect-port/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-detect-port/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-detect-port/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-detect-port/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-detect-port/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-detect-port/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-detect-port/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-detect-port/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-detect-port/build/test-report.html](https://npmtest.github.io/node-npmtest-detect-port/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-detect-port/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-detect-port/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-detect-port/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-detect-port/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-detect-port/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-detect-port/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-detect-port/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-detect-port/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "detect-port",
    "version": "1.1.1",
    "description": "detect available port",
    "keywords": [
        "detect",
        "port"
    ],
    "bin": {
        "detect": "./bin/detect-port",
        "detect-port": "./bin/detect-port"
    },
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/detect-port.git"
    },
    "dependencies": {
        "debug": "^2.6.0"
    },
    "devDependencies": {
        "command-line-test": "^1.0.8",
        "egg-bin": "^1.10.3",
        "egg-ci": "^1.1.0",
        "eslint": "^3.13.1",
        "eslint-config-egg": "^3.1.0",
        "pedding": "^1.1.0"
    },
    "scripts": {
        "test": "egg-bin test",
        "ci": "npm run lint && egg-bin cov",
        "lint": "eslint ."
    },
    "engines": {
        "node": ">= 4.2.1"
    },
    "ci": {
        "version": "4, 6, 7"
    },
    "homepage": "https://github.com/node-modules/detect-port",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
