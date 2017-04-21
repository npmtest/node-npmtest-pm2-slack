# npmtest-pm2-slack

#### basic test coverage for  [pm2-slack (v0.3.3)](https://github.com/mattpker/pm2-slack)  [![npm package](https://img.shields.io/npm/v/npmtest-pm2-slack.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pm2-slack) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pm2-slack.svg)](https://travis-ci.org/npmtest/node-npmtest-pm2-slack)

#### A PM2 module to emit events to Slack

[![NPM](https://nodei.co/npm/pm2-slack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pm2-slack)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pm2-slack/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-slack/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-slack/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pm2-slack/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-slack/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pm2-slack/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pm2-slack/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pm2-slack/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pm2-slack/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-slack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pm2-slack/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pm2-slack/build/test-report.html](https://npmtest.github.io/node-npmtest-pm2-slack/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pm2-slack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pm2-slack/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pm2-slack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pm2-slack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2-slack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2-slack/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pm2-slack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pm2-slack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pm2-slack",
    "version": "0.3.3",
    "description": "A PM2 module to emit events to Slack",
    "main": "index.js",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/mattpker/pm2-slack"
    },
    "keywords": [
        "pm2",
        "slack"
    ],
    "author": "Matt Atkinson <mattpker@gmail.com> (https://github.com/mattpker)",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/mattpker/pm2-slack/blob/master/LICENSE"
        }
    ],
    "bugs": {
        "url": "https://github.com/mattpker/pm2-slack/issues"
    },
    "homepage": "https://github.com/mattpker/pm2-slack",
    "dependencies": {
        "pm2": "^0.15.10",
        "pmx": "^0.5.5",
        "request": "^2.67.0"
    },
    "config": {
        "slack_url": null,
        "log": false,
        "error": true,
        "kill": true,
        "exception": true,
        "restart": false,
        "reload": false,
        "delete": false,
        "stop": false,
        "restart overlimit": true,
        "exit": false,
        "start": false,
        "online": false,
        "buffer": true,
        "buffer_seconds": 1,
        "queue_max": 100
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
