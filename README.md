# npmtest-temp

#### basic test coverage for  temp (v0.8.3)  [![npm package](https://img.shields.io/npm/v/npmtest-temp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-temp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-temp.svg)](https://travis-ci.org/npmtest/node-npmtest-temp)

#### Temporary files and directories

[![NPM](https://nodei.co/npm/temp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/temp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-temp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-temp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-temp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-temp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-temp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-temp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-temp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-temp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-temp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-temp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-temp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-temp/build/test-report.html](https://npmtest.github.io/node-npmtest-temp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-temp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-temp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-temp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-temp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-temp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-temp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-temp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-temp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "temp",
    "description": "Temporary files and directories",
    "tags": [
        "temporary",
        "temp",
        "tempfile",
        "tempdir",
        "tmpfile",
        "tmpdir",
        "security"
    ],
    "version": "0.8.3",
    "author": "Bruce Williams <brwcodes@gmail.com>",
    "license": "MIT",
    "directories": {
        "lib": "lib"
    },
    "engines": [
        "node >=0.8.0"
    ],
    "main": "./lib/temp",
    "dependencies": {
        "os-tmpdir": "^1.0.0",
        "rimraf": "~2.2.6"
    },
    "keywords": [
        "temporary",
        "tmp",
        "temp",
        "tempdir",
        "tempfile",
        "tmpdir",
        "tmpfile"
    ],
    "devDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/bruce/node-temp.git"
    },
    "scripts": {
        "test": "node test/temp-test.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
