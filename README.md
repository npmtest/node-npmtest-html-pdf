# npmtest-html-pdf

#### basic test coverage for  [html-pdf (v2.1.0)](https://github.com/marcbachmann/node-html-pdf)  [![npm package](https://img.shields.io/npm/v/npmtest-html-pdf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html-pdf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html-pdf.svg)](https://travis-ci.org/npmtest/node-npmtest-html-pdf)

#### HTML to PDF converter that uses phantomjs

[![NPM](https://nodei.co/npm/html-pdf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html-pdf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html-pdf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-pdf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html-pdf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html-pdf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html-pdf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html-pdf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html-pdf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html-pdf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html-pdf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html-pdf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html-pdf/build/test-report.html](https://npmtest.github.io/node-npmtest-html-pdf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html-pdf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html-pdf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html-pdf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-pdf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html-pdf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html-pdf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marc Bachmann"
    },
    "bin": {
        "html-pdf": "bin/index.js"
    },
    "bugs": {
        "url": "https://github.com/marcbachmann/node-html-pdf/issues"
    },
    "dependencies": {
        "phantomjs-prebuilt": "^2.1.4"
    },
    "description": "HTML to PDF converter that uses phantomjs",
    "devDependencies": {
        "coffee-script": "^1.7.1",
        "standard": "^5.1.1",
        "tap-spec": "^2.2.0",
        "tape": "^3.4.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "c34d518f7f802ffbc834bf80279cfce7da2cce4b",
        "tarball": "https://registry.npmjs.org/html-pdf/-/html-pdf-2.1.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "d7ae2439ef8082475a80f3045ddfa6dce7c5054e",
    "homepage": "https://github.com/marcbachmann/node-html-pdf",
    "keywords": [
        "html",
        "pdf",
        "phantom",
        "phantomjs",
        "nodejs"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "marcbachmann"
        }
    ],
    "name": "html-pdf",
    "optionalDependencies": {
        "phantomjs-prebuilt": "^2.1.4"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/marcbachmann/node-html-pdf.git"
    },
    "scripts": {
        "standard": "standard bin/index.js",
        "test": "npm run standard && node test/index.js"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
