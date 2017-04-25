# npmtest-serve-static

#### basic test coverage for  [serve-static (v1.12.1)](https://github.com/expressjs/serve-static#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-serve-static.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-serve-static) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-serve-static.svg)](https://travis-ci.org/npmtest/node-npmtest-serve-static)

#### Serve static files

[![NPM](https://nodei.co/npm/serve-static.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/serve-static)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-serve-static/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-serve-static/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-serve-static/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-serve-static/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-serve-static/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-serve-static/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-serve-static/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-serve-static/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-serve-static/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-serve-static/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-serve-static/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-serve-static/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-serve-static/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-serve-static/build/test-report.html](https://npmtest.github.io/node-npmtest-serve-static/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-serve-static/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-serve-static/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-serve-static/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-serve-static/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-serve-static/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-serve-static/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-serve-static/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-serve-static/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Douglas Christopher Wilson"
    },
    "bugs": {
        "url": "https://github.com/expressjs/serve-static/issues"
    },
    "dependencies": {
        "encodeurl": "~1.0.1",
        "escape-html": "~1.0.3",
        "parseurl": "~1.3.1",
        "send": "0.15.1"
    },
    "description": "Serve static files",
    "devDependencies": {
        "eslint": "3.17.0",
        "eslint-config-standard": "7.0.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7443a965e3ced647aceb5639fa06bf4d1bbe0039",
        "tarball": "https://registry.npmjs.org/serve-static/-/serve-static-1.12.1.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "3e6e778fcf6c88dcf659b8f1d5f06be2eebbe2db",
    "homepage": "https://github.com/expressjs/serve-static#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "serve-static",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/serve-static.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/"
    },
    "version": "1.12.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
