# npmtest-babel-plugin-import

#### test coverage for  babel-plugin-import (v1.1.1)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-plugin-import.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-plugin-import) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-plugin-import.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-plugin-import)

#### Component modular import plugin for babel.

[![NPM](https://nodei.co/npm/babel-plugin-import.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-import)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-plugin-import/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-plugin-import/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-plugin-import/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-plugin-import/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-plugin-import/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-plugin-import/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-plugin-import/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-import/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-plugin-import/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "chencheng"
    },
    "babel": {
        "presets": [
            "es2015",
            "stage-0"
        ],
        "plugins": [
            "add-module-exports"
        ]
    },
    "dependencies": {},
    "description": "Component modular import plugin for babel.",
    "devDependencies": {
        "babel-cli": "^6.3.13",
        "babel-core": "^6.18.0",
        "babel-istanbul": "^0.7.0",
        "babel-plugin-add-module-exports": "^0.1.2",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "coveralls": "^2.11.6",
        "eslint": "^2.7.0",
        "eslint-config-airbnb": "^6.2.0",
        "expect": "^1.13.4",
        "material-ui": "^0.15.4",
        "mocha": "^2.3.4",
        "pre-commit": "~1.1.2",
        "react-toolbox": "^1.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "98977e6e9cef92bffef04bb1f291c44039fe21c6",
        "tarball": "https://registry.npmjs.org/babel-plugin-import/-/babel-plugin-import-1.1.1.tgz"
    },
    "files": [
        "lib",
        "package.json",
        "README.md"
    ],
    "gitHead": "f277fcd359e8bc1dd4784acf42d6241a7073d70f",
    "keywords": [
        "babel-plugin",
        "antd"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "afc163"
        },
        {
            "name": "sorrycc"
        }
    ],
    "name": "babel-plugin-import",
    "optionalDependencies": {},
    "pre-commit": [
        "lint"
    ],
    "scripts": {
        "build": "rm -rf lib && ./node_modules/.bin/babel src --out-dir lib --ignore __tests__",
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "debug": "mocha --require babel-core/register --require babel-polyfill --no-timeouts",
        "lint": "eslint --ext .js src",
        "test": "babel-node node_modules/.bin/babel-istanbul cover node_modules/.bin/_mocha --no-timeouts"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
