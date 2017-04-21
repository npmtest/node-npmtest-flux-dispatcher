# npmtest-flux-dispatcher

#### basic test coverage for  [flux-dispatcher (v1.1.5)](https://github.com/jedireza/flux-dispatcher)  [![npm package](https://img.shields.io/npm/v/npmtest-flux-dispatcher.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-flux-dispatcher) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-flux-dispatcher.svg)](https://travis-ci.org/npmtest/node-npmtest-flux-dispatcher)

#### A Flux dispatcher ready for action.

[![NPM](https://nodei.co/npm/flux-dispatcher.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/flux-dispatcher)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-flux-dispatcher/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-flux-dispatcher/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-flux-dispatcher/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-flux-dispatcher/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-flux-dispatcher/build/test-report.html](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-flux-dispatcher/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-flux-dispatcher/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-flux-dispatcher/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-flux-dispatcher/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-flux-dispatcher/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "flux-dispatcher",
    "version": "1.1.5",
    "description": "A Flux dispatcher ready for action.",
    "main": "index.js",
    "scripts": {
        "test": "lab -c -L",
        "test-cover": "lab -c -r html -o ./test/artifacts/coverage.html && open ./test/artifacts/coverage.html"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/jedireza/flux-dispatcher"
    },
    "keywords": [
        "flux",
        "dispatcher",
        "react"
    ],
    "author": "Reza Akhavan <jedireza@gmail.com> (http://reza.akhavan.me/)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/jedireza/flux-dispatcher/issues"
    },
    "homepage": "https://github.com/jedireza/flux-dispatcher",
    "peerDependencies": {
        "flux": "2.x.x"
    },
    "devDependencies": {
        "code": "3.x.x",
        "eslint-config-hapi": "10.x.x",
        "eslint-plugin-hapi": "4.x.x",
        "flux": "2.x.x",
        "lab": "11.x.x"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
