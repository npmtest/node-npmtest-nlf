# npmtest-nlf

#### basic test coverage for  [nlf (v1.4.3)](https://github.com/iandotkelly/nlf)  [![npm package](https://img.shields.io/npm/v/npmtest-nlf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nlf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nlf.svg)](https://travis-ci.org/npmtest/node-npmtest-nlf)

#### Find licenses for a node application and its node_module dependencies

[![NPM](https://nodei.co/npm/nlf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nlf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nlf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nlf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nlf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nlf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nlf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nlf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nlf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nlf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nlf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nlf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nlf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nlf/build/test-report.html](https://npmtest.github.io/node-npmtest-nlf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nlf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nlf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nlf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nlf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nlf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nlf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nlf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nlf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nlf",
    "title": "Node License Finder",
    "description": "Find licenses for a node application and its node_module dependencies",
    "author": "Ian Kelly <iandotkelly@gmail.com>",
    "version": "1.4.3",
    "license": "MIT",
    "bin": {
        "nlf": "./bin/nlf-cli.js"
    },
    "homepage": "https://github.com/iandotkelly/nlf",
    "repository": {
        "type": "git",
        "url": "git://github.com/iandotkelly/nlf.git"
    },
    "dependencies": {
        "archy": "1.0.0",
        "commander": "2.9.0",
        "compare-versions": "3.0.0",
        "glob-all": "3.1.0  ",
        "read-installed": "4.0.3"
    },
    "devDependencies": {
        "gulp": "^3.9.1",
        "gulp-coverage": "^0.3.36",
        "gulp-coveralls": "^0.1.3",
        "gulp-jshint": "^2.0.0",
        "gulp-mocha": "^3.0.0",
        "jshint": "^2.9.1",
        "should": "^11.2.0"
    },
    "engines": {
        "node": ">=0.10"
    },
    "keywords": [
        "license",
        "licence",
        "checker",
        "finder",
        "audit",
        "legal",
        "dependency",
        "cli"
    ],
    "scripts": {
        "test": "gulp travis"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
