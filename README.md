# npmtest-botkit

#### basic test coverage for  [botkit (v0.5.2)](https://botkit.ai)  [![npm package](https://img.shields.io/npm/v/npmtest-botkit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-botkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-botkit.svg)](https://travis-ci.org/npmtest/node-npmtest-botkit)

#### Building blocks for Building Bots

[![NPM](https://nodei.co/npm/botkit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/botkit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-botkit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-botkit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-botkit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-botkit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-botkit/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-botkit/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-botkit/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-botkit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-botkit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-botkit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-botkit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-botkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-botkit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-botkit/build/test-report.html](https://npmtest.github.io/node-npmtest-botkit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-botkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-botkit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-botkit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-botkit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-botkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-botkit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-botkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-botkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ben@howdy.ai"
    },
    "bugs": {
        "url": "https://github.com/howdyai/botkit/issues"
    },
    "dependencies": {
        "async": "^2.0.0-rc.5",
        "back": "^1.0.1",
        "body-parser": "^1.14.2",
        "botbuilder": "^3.2.3",
        "botkit-studio-sdk": "^1.0.0",
        "ciscospark": "^0.7.31",
        "clone": "2.0.0",
        "command-line-args": "^3.0.0",
        "crypto": "0.0.3",
        "express": "^4.13.3",
        "https-proxy-agent": "^1.0.0",
        "jfs": "^0.2.6",
        "localtunnel": "^1.8.1",
        "md5": "^2.1.0",
        "mustache": "^2.2.1",
        "promise": "^7.1.1",
        "randomstring": "^1.1.5",
        "request": "^2.67.0",
        "twilio": "^2.9.1",
        "url": "^0.11.0",
        "ware": "^1.3.0",
        "ws": "^1.1.1"
    },
    "description": "Building blocks for Building Bots",
    "devDependencies": {
        "jscs": "^2.7.0",
        "mocha": "^2.4.5",
        "should": "^8.0.2",
        "should-sinon": "0.0.5",
        "sinon": "^1.17.7",
        "winston": "^2.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "4be4261cbdd81ba70d7dab225864c87d6bb4ad81",
        "tarball": "https://registry.npmjs.org/botkit/-/botkit-0.5.2.tgz"
    },
    "gitHead": "5e14ba95c6de4d9ef245e9bd04265cfa3c2c1e59",
    "homepage": "https://botkit.ai",
    "keywords": [
        "bots",
        "chatbots",
        "slack",
        "cisco spark",
        "facebook messenger",
        "twilio ipm",
        "microsoft bot framework"
    ],
    "license": "MIT",
    "main": "lib/Botkit.js",
    "maintainers": [
        {
            "name": "xoxco"
        }
    ],
    "name": "botkit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/howdyai/botkit.git"
    },
    "scripts": {
        "pretest": "jscs ./lib/",
        "test": "mocha tests/*.js"
    },
    "version": "0.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
