# npmtest-tv4

#### basic test coverage for  tv4 (v1.3.0)  [![npm package](https://img.shields.io/npm/v/npmtest-tv4.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tv4) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tv4.svg)](https://travis-ci.org/npmtest/node-npmtest-tv4)

#### A public domain JSON Schema validator for JavaScript

[![NPM](https://nodei.co/npm/tv4.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tv4)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tv4/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tv4/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tv4/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tv4/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tv4/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tv4/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tv4/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tv4/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tv4/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tv4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tv4/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tv4/build/test-report.html](https://npmtest.github.io/node-npmtest-tv4/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tv4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tv4/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tv4/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tv4/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tv4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tv4/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tv4/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tv4/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "tv4",
    "version": "1.3.0",
    "author": "Geraint Luff",
    "description": "A public domain JSON Schema validator for JavaScript",
    "keywords": [
        "json-schema",
        "schema",
        "validator",
        "tv4"
    ],
    "maintainers": [
        {
            "name": "Geraint Luff",
            "web": "https://github.com/geraintluff/"
        }
    ],
    "main": "tv4.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/geraintluff/tv4.git"
    },
    "license": [
        {
            "type": "Public Domain",
            "url": "http://geraintluff.github.io/tv4/LICENSE.txt"
        },
        {
            "type": "MIT",
            "url": "http://jsonary.com/LICENSE.txt"
        }
    ],
    "devDependencies": {
        "grunt": "~0.4.1",
        "grunt-cli": "~0.1.9",
        "grunt-component-io": "~0.1.0",
        "grunt-concat-sourcemap": "~0.2",
        "grunt-contrib-clean": "~0.4.1",
        "grunt-contrib-copy": "~0.4.1",
        "grunt-contrib-jshint": "~0.6.2",
        "grunt-contrib-uglify": "~0.2.2",
        "grunt-markdown": "~0.3.0",
        "grunt-mocha": "~0.4",
        "grunt-mocha-test": "~0.5.0",
        "grunt-push-release": "~0.1.1",
        "grunt-regex-replace": "~0.2.5",
        "jshint-path-reporter": "~0.1",
        "mocha": "~1.11.0",
        "mocha-unfunk-reporter": "~0.2",
        "proclaim": "1.4",
        "requirejs": "~2.1.11",
        "source-map-support": "~0.1"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "scripts": {
        "test": "grunt test",
        "prepublish": "grunt prepublish"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
