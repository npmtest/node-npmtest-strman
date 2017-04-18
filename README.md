# npmtest-strman

#### test coverage for  [strman (v2.0.0)](https://github.com/dleitee/strman#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-strman.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-strman) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-strman.svg)](https://travis-ci.org/npmtest/node-npmtest-strman)

#### A Javascript string manipulation library without npm dependences.

[![NPM](https://nodei.co/npm/strman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/strman)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-strman/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-strman/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-strman/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-strman/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-strman/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-strman/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-strman/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-strman/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-strman/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-strman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-strman/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-strman/build/test-report.html](https://npmtest.github.io/node-npmtest-strman/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-strman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-strman/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-strman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-strman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strman/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-strman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-strman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Leite de Oliveira"
    },
    "babel": {
        "presets": [
            "es2015",
            "stage-0"
        ]
    },
    "bugs": {
        "url": "https://github.com/dleitee/strman/issues"
    },
    "dependencies": {},
    "description": "A Javascript string manipulation library without npm dependences.",
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-core": "^6.7.6",
        "babel-eslint": "^7.1.1",
        "babel-istanbul": "^0.8.0",
        "babel-jest": "^19.0.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-remove-import": "^1.0.0",
        "babel-plugin-transform-remove-strict-mode": "^0.0.2",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-stage-0": "^6.22.0",
        "babel-register": "^6.7.2",
        "coveralls": "^2.11.9",
        "dox": "^0.9.0",
        "eslint": "^3.16.1",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-no-lenght": "^1.0.2-0",
        "jest": "^19.0.2",
        "jsdoc": "^3.4.3",
        "jsdoc-babel": "^0.3.0",
        "minami": "^1.1.1",
        "showdeps": "^1.0.0",
        "yarn": "^0.19.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "7a13d89bb0a0001d6a527ab41ea66d0816061cfd",
        "tarball": "https://registry.npmjs.org/strman/-/strman-2.0.0.tgz"
    },
    "eslintConfig": {
        "parser": "babel-eslint",
        "extends": "airbnb/base",
        "env": {
            "browser": true,
            "node": true,
            "jest": true
        },
        "rules": {
            "semi": [
                2,
                "never"
            ],
            "no-console": [
                2,
                {
                    "allow": [
                        "warn",
                        "info",
                        "error"
                    ]
                }
            ],
            "import/named": 2,
            "no-multiple-empty-lines": [
                "error",
                {
                    "max": 1,
                    "maxEOF": 1,
                    "maxBOF": 0
                }
            ],
            "import/order": [
                "error",
                {
                    "groups": [
                        "builtin",
                        "external",
                        "parent",
                        "sibling",
                        "index"
                    ],
                    "newlines-between": "always"
                }
            ],
            "no-lenght/no-lenght": "error"
        },
        "plugins": [
            "no-lenght"
        ]
    },
    "gitHead": "3f85db8997a0867f1d9a6f4785adbab219bfaf3b",
    "homepage": "https://github.com/dleitee/strman#readme",
    "keywords": [
        "string",
        "manipulate",
        "str",
        "manipulation",
        "strman"
    ],
    "license": "MIT",
    "main": "lib/strman.js",
    "maintainers": [
        {
            "name": "dleitee"
        }
    ],
    "name": "strman",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dleitee/strman.git"
    },
    "scripts": {
        "build:packages": "babel-node build/build.js",
        "build:strman": "babel src --out-dir lib",
        "coveralls": "cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "docs": "jsdoc --configure .jsdocrc --verbose -r",
        "lint": "eslint src tests",
        "postpublish": "rm -rf ./lib",
        "prepublish": "npm run build:strman",
        "test": "jest --coverage --expand",
        "test-watch": "jest --watch"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
