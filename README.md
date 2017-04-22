# npmtest-react-router-component

#### basic test coverage for  [react-router-component (v0.36.5)](http://strml.viewdocs.io/react-router-component)  [![npm package](https://img.shields.io/npm/v/npmtest-react-router-component.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-router-component) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-router-component.svg)](https://travis-ci.org/npmtest/node-npmtest-react-router-component)

#### Declarative router component for React

[![NPM](https://nodei.co/npm/react-router-component.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-router-component)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-router-component/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-router-component/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-router-component/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-router-component/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-router-component/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-router-component/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-router-component/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-router-component/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-router-component/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-router-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-router-component/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-router-component/build/test-report.html](https://npmtest.github.io/node-npmtest-react-router-component/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-router-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-router-component/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-router-component/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-router-component/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-router-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-router-component/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-router-component/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-router-component/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrey Popp",
        "url": "https://github.com/andreypopp"
    },
    "browserify": {
        "transform": [
            "envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/strml/react-router-component/issues"
    },
    "contributors": [
        {
            "name": "Dave Mac",
            "url": "https://github.com/DveMac"
        },
        {
            "name": "Matthew Dapena-Tretter",
            "url": "https://github.com/matthewwithanm"
        },
        {
            "name": "Mitchel Kuijpers",
            "url": "https://github.com/mitchelkuijpers"
        },
        {
            "name": "Simen Brekken",
            "url": "https://github.com/sbrekken"
        },
        {
            "name": "Samuel Reed",
            "url": "https://github.com/strml"
        }
    ],
    "dependencies": {
        "is-equal-shallow": "^0.1.3",
        "object-assign": "^4.1.0",
        "object.omit": "^2.0.0",
        "qs": "^6.2.0",
        "url-pattern": "~1.0.1",
        "urllite": "~0.5.0"
    },
    "description": "Declarative router component for React",
    "devDependencies": {
        "babel": "^6.5.2",
        "babel-cli": "^6.10.1",
        "babel-eslint": "^7.1.1",
        "babel-plugin-espower": "^2.2.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.5.0",
        "eslint": "^3.16.1",
        "eslint-plugin-react": "^6.10.0",
        "mocha": "^3.2.0",
        "power-assert": "^1.4.1",
        "pre-commit": "^1.2.2",
        "react": "^15.1.0",
        "react-dom": "^15.1.0",
        "semver": "^5.1.0",
        "zuul": "3.10.1"
    },
    "directories": {},
    "dist": {
        "shasum": "61075267fe5d427ddeaaa117a45222df8710712e",
        "tarball": "https://registry.npmjs.org/react-router-component/-/react-router-component-0.36.5.tgz"
    },
    "gitHead": "c01b674e5dc7e664bb61e2fc6a8114a679cbccf7",
    "homepage": "http://strml.viewdocs.io/react-router-component",
    "keywords": [
        "react",
        "react-component",
        "router",
        "history",
        "pushState"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "andreypopp"
        },
        {
            "name": "strml"
        }
    ],
    "name": "react-router-component",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^=0.14.0 || ^15.0.0"
    },
    "pre-commit": [
        "lint",
        "test"
    ],
    "publishConfig": {
        "registry": "https://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/strml/react-router-component.git"
    },
    "scripts": {
        "lint": "make lint",
        "test": "make test"
    },
    "version": "0.36.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
