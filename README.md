# npmtest-anyproxy

#### basic test coverage for  [anyproxy (v3.10.4)](https://github.com/alibaba/anyproxy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-anyproxy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-anyproxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-anyproxy.svg)](https://travis-ci.org/npmtest/node-npmtest-anyproxy)

#### A fully configurable proxy in NodeJS, which can handle HTTPS requests perfectly.

[![NPM](https://nodei.co/npm/anyproxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/anyproxy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-anyproxy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-anyproxy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-anyproxy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-anyproxy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-anyproxy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-anyproxy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-anyproxy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-anyproxy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-anyproxy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-anyproxy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-anyproxy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-anyproxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-anyproxy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-anyproxy/build/test-report.html](https://npmtest.github.io/node-npmtest-anyproxy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-anyproxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-anyproxy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-anyproxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-anyproxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-anyproxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-anyproxy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-anyproxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-anyproxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ottomao@gmail.com"
    },
    "bin": {
        "anyproxy": "bin.js"
    },
    "bugs": {
        "url": "https://github.com/alibaba/anyproxy/issues"
    },
    "dependencies": {
        "async": "~0.9.0",
        "async-task-mgr": ">=1.1.0",
        "body-parser": "^1.13.1",
        "change-case": "^3.0.0",
        "colorful": "^2.1.0",
        "commander": "~2.3.0",
        "compression": "^1.4.4",
        "express": "^4.8.5",
        "iconv-lite": "^0.4.6",
        "ip": "^0.3.2",
        "juicer": "^0.6.6-stable",
        "mime-types": "2.1.11",
        "nedb": "^0.11.0",
        "node-easy-cert": "^1.0.0",
        "node-forge": "^0.6.39",
        "npm": "^2.7.0",
        "promise": "^7.0.4",
        "qrcode-npm": "0.0.3",
        "stream-throttle": "^0.1.3",
        "ws": "^1.1.0"
    },
    "description": "A fully configurable proxy in NodeJS, which can handle HTTPS requests perfectly.",
    "devDependencies": {
        "babel-polyfill": "^6.13.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-stage-0": "^6.5.0",
        "babel-register": "^6.11.6",
        "https-proxy-agent": "^1.0.0",
        "jasmine": "^2.4.1",
        "koa": "^1.2.1",
        "koa-body": "^1.4.0",
        "koa-router": "^5.4.0",
        "koa-send": "^3.2.0",
        "koa-websocket": "^2.0.0",
        "nodeunit": "^0.9.1",
        "request": "^2.74.0",
        "stream-equal": "0.1.8"
    },
    "directories": {},
    "dist": {
        "shasum": "930d286ca071515c19787086cc036f64d9667376",
        "tarball": "https://registry.npmjs.org/anyproxy/-/anyproxy-3.10.4.tgz"
    },
    "gitHead": "26a05e8c5c7b6173811320e3dc20ac9aed61b494",
    "homepage": "https://github.com/alibaba/anyproxy#readme",
    "license": "ISC",
    "main": "proxy.js",
    "maintainers": [
        {
            "name": "ottomao"
        },
        {
            "name": "alexyan"
        }
    ],
    "name": "anyproxy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alibaba/anyproxy.git"
    },
    "scripts": {
        "test": "sh test/test.sh",
        "testserver": "node test/server/startServer.js"
    },
    "version": "3.10.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
