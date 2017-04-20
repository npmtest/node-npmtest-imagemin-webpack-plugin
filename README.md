# npmtest-imagemin-webpack-plugin

#### basic test coverage for  [imagemin-webpack-plugin (v1.4.4)](https://github.com/Klathmon/imagemin-webpack-plugin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-imagemin-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-imagemin-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-imagemin-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-imagemin-webpack-plugin)

#### Webpack plugin to compress images

[![NPM](https://nodei.co/npm/imagemin-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imagemin-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-imagemin-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-imagemin-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-imagemin-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imagemin-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imagemin-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imagemin-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-imagemin-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gregory Benner",
        "url": "https://github.com/Klathmon"
    },
    "babel": {
        "plugins": [
            "transform-runtime",
            "transform-object-rest-spread"
        ],
        "presets": [
            [
                "env",
                {
                    "targets": {
                        "node": 4
                    }
                }
            ]
        ]
    },
    "bugs": {
        "url": "https://github.com/Klathmon/imagemin-webpack-plugin/issues"
    },
    "dependencies": {
        "async-throttle": "^1.0.0",
        "babel-runtime": "^6.18.0",
        "imagemin": "^5.2.1",
        "imagemin-gifsicle": "^5.1.0",
        "imagemin-jpegtran": "^5.0.2",
        "imagemin-optipng": "^5.1.0",
        "imagemin-pngquant": "^5.0.0",
        "imagemin-svgo": "^5.1.0",
        "lodash.map": "^4.6.0",
        "minimatch": "^3.0.3",
        "webpack-sources": "^0.1.3"
    },
    "description": "Webpack plugin to compress images",
    "devDependencies": {
        "babel-cli": "6.18.0",
        "babel-plugin-transform-object-rest-spread": "6.19.0",
        "babel-plugin-transform-runtime": "6.15.0",
        "babel-preset-env": "0.0.8",
        "gulp": "3.9.1",
        "gulp-npm-script-sync": "1.1.0",
        "gulp-run-command": "0.0.7",
        "np": "2.10.1",
        "rimraf": "2.5.4",
        "standard": "8.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "384684442bfca52594677aa9e2f6d90b2fd38bea",
        "tarball": "https://registry.npmjs.org/imagemin-webpack-plugin/-/imagemin-webpack-plugin-1.4.4.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "fe5f803a04b9ef165f0ab6f31cd59494b2d7ae24",
    "homepage": "https://github.com/Klathmon/imagemin-webpack-plugin#readme",
    "license": "MIT",
    "main": "index.es5.js",
    "maintainers": [
        {
            "name": "klathmon"
        }
    ],
    "name": "imagemin-webpack-plugin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Klathmon/imagemin-webpack-plugin.git"
    },
    "scripts": {
        "build": "gulp build",
        "clean": "gulp clean",
        "prepublish": "gulp build",
        "preversion": "gulp build",
        "test": "gulp test"
    },
    "standard": {},
    "version": "1.4.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
