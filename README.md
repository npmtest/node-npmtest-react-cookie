# npmtest-react-cookie

#### basic test coverage for  [react-cookie (v2.0.6)](https://github.com/reactivestack/cookies/packages/react-cookie/#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-cookie.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-cookie) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-cookie.svg)](https://travis-ci.org/npmtest/node-npmtest-react-cookie)

#### Universal cookies for React

[![NPM](https://nodei.co/npm/react-cookie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-cookie)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-cookie/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-cookie/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-cookie/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-cookie/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-cookie/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-cookie/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-cookie/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-cookie/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-cookie/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-cookie/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-cookie/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-cookie/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-cookie/build/test-report.html](https://npmtest.github.io/node-npmtest-react-cookie/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-cookie/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-cookie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-cookie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-cookie/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-cookie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-cookie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Benoit Tremblay"
    },
    "bugs": {
        "url": "https://github.com/reactivestack/cookies/issues"
    },
    "dependencies": {
        "hoist-non-react-statics": "^1.2.0",
        "prop-types": "^15.0.0",
        "react": "^15.0.0",
        "universal-cookie": "^2.0.1"
    },
    "description": "Universal cookies for React",
    "devDependencies": {
        "babel-cli": "^6.24.1",
        "react-dom": "^15.0.0",
        "rimraf": "^2.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "8db17f772494896dc9f2c25d9c3e581617bab735",
        "tarball": "https://registry.npmjs.org/react-cookie/-/react-cookie-2.0.6.tgz"
    },
    "files": [
        "lib"
    ],
    "homepage": "https://github.com/reactivestack/cookies/packages/react-cookie/#readme",
    "keywords": [
        "universal",
        "isomophic",
        "cookie",
        "react"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "exon"
        }
    ],
    "name": "react-cookie",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactivestack/cookies.git"
    },
    "scripts": {
        "build": "rimraf lib && babel src -d lib --ignore __tests__"
    },
    "version": "2.0.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
