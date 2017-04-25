# npmtest-webworkify

#### basic test coverage for  [webworkify (v1.4.0)](https://github.com/substack/webworkify)  [![npm package](https://img.shields.io/npm/v/npmtest-webworkify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webworkify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webworkify.svg)](https://travis-ci.org/npmtest/node-npmtest-webworkify)

#### launch a web worker that can require() in the browser with browserify

[![NPM](https://nodei.co/npm/webworkify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webworkify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webworkify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webworkify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webworkify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webworkify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webworkify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-webworkify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-webworkify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webworkify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webworkify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webworkify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webworkify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webworkify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webworkify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webworkify/build/test-report.html](https://npmtest.github.io/node-npmtest-webworkify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webworkify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webworkify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webworkify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webworkify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webworkify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webworkify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webworkify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webworkify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/webworkify/issues"
    },
    "dependencies": {},
    "description": "launch a web worker that can require() in the browser with browserify",
    "devDependencies": {
        "gamma": "~0.1.0",
        "tape": "~1.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "71245d1e34cacf54e426bd955f8cc6ee12d024c2",
        "tarball": "https://registry.npmjs.org/webworkify/-/webworkify-1.4.0.tgz"
    },
    "gitHead": "ed584efa99a2ecaf23905b7926e0575e7c7a4761",
    "homepage": "https://github.com/substack/webworkify",
    "keywords": [
        "web",
        "worker",
        "background",
        "browser",
        "fork"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "anandthakker"
        },
        {
            "name": "substack"
        }
    ],
    "name": "webworkify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/webworkify.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
