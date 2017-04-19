# npmtest-local-links

#### test coverage for  [local-links (v1.4.1)](https://github.com/lukekarrys/local-links)  [![npm package](https://img.shields.io/npm/v/npmtest-local-links.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-local-links) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-local-links.svg)](https://travis-ci.org/npmtest/node-npmtest-local-links)

#### Determine cross-browser if an event or anchor element should be handled locally.

[![NPM](https://nodei.co/npm/local-links.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/local-links)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-local-links/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-local-links/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-local-links/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-local-links/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-local-links/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-local-links/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-local-links/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-local-links/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-local-links/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-local-links/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-local-links/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-local-links/build/test-report.html](https://npmtest.github.io/node-npmtest-local-links/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-local-links/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-local-links/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-local-links/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-local-links/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-local-links/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-local-links/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-local-links/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-local-links/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Luke Karrys"
    },
    "bugs": {
        "url": "https://github.com/lukekarrys/local-links/issues"
    },
    "dependencies": {},
    "description": "Determine cross-browser if an event or anchor element should be handled locally.",
    "devDependencies": {
        "browserify": "^13.1.0",
        "electron-prebuilt": "^1.3.2",
        "git-validate": "^2.1.4",
        "jquery": "^3.1.0",
        "lodash.partial": "^4.2.0",
        "run-browser": "^2.0.2",
        "standard": "^8.0.0-beta.3",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.0",
        "tape-run": "^2.1.4",
        "zuul": "^3.10.3",
        "zuul-ngrok": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bfc94f3d09cc444f0d14408f80f9c59292c57e35",
        "tarball": "https://registry.npmjs.org/local-links/-/local-links-1.4.1.tgz"
    },
    "gitHead": "792ba70eb3193b08ae958f21b6e33fb09dfdae13",
    "homepage": "https://github.com/lukekarrys/local-links",
    "keywords": [
        "IE",
        "links",
        "local"
    ],
    "license": "MIT",
    "main": "local-links.js",
    "maintainers": [
        {
            "name": "lukekarrys"
        }
    ],
    "name": "local-links",
    "optionalDependencies": {},
    "pre-commit": [
        "lint",
        "test",
        "validate"
    ],
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/lukekarrys/local-links.git"
    },
    "scripts": {
        "lint": "standard",
        "start": "run-browser test/index.js",
        "start-80": "run-browser test/index.js --port 80",
        "test": "browserify test/index.js | tape-run -b electron | tap-spec",
        "test-travis": "npm test && npm run zuul",
        "validate": "npm ls",
        "zuul": "zuul --ui tape -- test/index.js",
        "zuul-local": "zuul --local 8080 --ui tape -- test/index.js"
    },
    "version": "1.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
