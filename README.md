# npmtest-electron-settings

#### test coverage for  [electron-settings (v3.0.14)](https://github.com/nathanbuchar/electron-settings#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-settings.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-settings) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-settings.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-settings)

#### A simple persistent user settings framework for Electron.

[![NPM](https://nodei.co/npm/electron-settings.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-settings)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-settings/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-settings/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-settings/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-settings/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-settings/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-settings/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-settings/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-settings/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-settings/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-settings/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-settings/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-settings/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-settings/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-settings/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-settings/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-settings/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-settings/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-settings/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-settings/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-settings/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-settings/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Buchar"
    },
    "bugs": {
        "url": "https://github.com/nathanbuchar/electron-settings/issues"
    },
    "dependencies": {
        "clone": "^2.1.1",
        "jsonfile": "^2.4.0"
    },
    "description": "A simple persistent user settings framework for Electron.",
    "devDependencies": {
        "electron": "^1.6.2",
        "electron-mocha": "^3.4.0",
        "eslint": "^3.18.0",
        "eslint-config-airbnb-base": "^11.1.2",
        "eslint-plugin-import": "^2.2.0",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f3605127f720ff66411bb8dde0b66f611f03885f",
        "tarball": "https://registry.npmjs.org/electron-settings/-/electron-settings-3.0.14.tgz"
    },
    "gitHead": "b24767d24f50324b5251c281306ab19da215e033",
    "homepage": "https://github.com/nathanbuchar/electron-settings#readme",
    "keywords": [
        "electron",
        "app",
        "user",
        "data",
        "settings",
        "config",
        "storage",
        "json",
        "has",
        "get",
        "getAll",
        "set",
        "setAll",
        "delete",
        "deleteAll",
        "watch",
        "file"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "nathanbuchar"
        }
    ],
    "name": "electron-settings",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nathanbuchar/electron-settings.git"
    },
    "scripts": {
        "test": "npm run test:main && npm run test:renderer",
        "test:main": "electron-mocha tests",
        "test:renderer": "electron-mocha tests --renderer"
    },
    "version": "3.0.14"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
