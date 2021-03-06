# npmtest-mosca

#### basic test coverage for  [mosca (v2.3.0)](https://github.com/mcollina/mosca#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mosca.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mosca) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mosca.svg)](https://travis-ci.org/npmtest/node-npmtest-mosca)

#### MQTT broker as a module

[![NPM](https://nodei.co/npm/mosca.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mosca)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mosca/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mosca/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mosca/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mosca/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mosca/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mosca/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mosca/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mosca/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mosca/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mosca/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mosca/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mosca/build/test-report.html](https://npmtest.github.io/node-npmtest-mosca/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mosca/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mosca/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mosca/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mosca/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mosca/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mosca/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mosca/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mosca/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo Collina"
    },
    "bin": {
        "mosca": "./bin/mosca"
    },
    "bugs": {
        "url": "http://github.com/mcollina/mosca/issues"
    },
    "dependencies": {
        "amqp": "~0.2.4",
        "array-from": "^2.1.1",
        "ascoltatori": "^3.0.0",
        "brfs": "~1.4.2",
        "clone": "^1.0.2",
        "commander": "~2.9.0",
        "deepcopy": "^0.6.1",
        "extend": "^3.0.0",
        "ioredis": "^1.15.1",
        "json-buffer": "~2.0.11",
        "jsonschema": "^1.0.3",
        "level-sublevel": "^6.5.2",
        "leveldown": "~1.4.3",
        "levelup": "^1.3.1",
        "lru-cache": "~4.0.0",
        "memdown": "~1.1.1",
        "minimatch": "~3.0.0",
        "moment": "~2.13.0",
        "mongodb": "~2.1.4",
        "moving-average": "0.1.1",
        "mqtt": "^1.6.3",
        "mqtt-connection": "^2.1.1",
        "msgpack5": "^3.3.0",
        "pbkdf2-password": "^1.1.0",
        "pino": "^2.4.2",
        "qlobber": "~0.7.0",
        "retimer": "^1.0.1",
        "shortid": "^2.2.4",
        "st": "~1.1.0",
        "steed": "^1.0.0",
        "uuid": "^2.0.1",
        "websocket-stream": "~3.1.0"
    },
    "description": "MQTT broker as a module",
    "devDependencies": {
        "browserify": "~13.0.0",
        "chai": "^3.5.0",
        "coveralls": "~2.11.1",
        "dox-foundation": "~0.5.4",
        "istanbul": "~0.4.0",
        "jshint": "~2.9.1",
        "mocha": "^2.0.1",
        "mongo-clean": "^1.1.0",
        "osenv": "^0.1.0",
        "pre-commit": "1.1.2",
        "rimraf": "^2.2.8",
        "sinon": "~1.7.0",
        "sinon-chai": "~2.8.0",
        "supertest": "~1.2.0",
        "tmp": "0.0.24",
        "uglify-js": "^2.4.16",
        "underscore": "^1.7.0",
        "ws": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "712fcbbcf52729dacb76faddee02e3b6dba5f578",
        "tarball": "https://registry.npmjs.org/mosca/-/mosca-2.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.12"
    },
    "gitHead": "697dffd2024a11badeb866d57f76648a65b6f844",
    "homepage": "https://github.com/mcollina/mosca#readme",
    "keywords": [
        "mqtt",
        "mqtt server",
        "publish",
        "subscribe",
        "pubsub",
        "rabbitmq",
        "zeromq",
        "0mq",
        "amqp",
        "mosquitto",
        "websocket"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "matteo.collina"
        }
    ],
    "name": "mosca",
    "optionalDependencies": {
        "amqp": "~0.2.4",
        "ioredis": "^1.15.1",
        "leveldown": "~1.4.3",
        "mongodb": "~2.1.4"
    },
    "pre-commit": [
        "jshint-lib",
        "jshint-test",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mcollina/mosca.git"
    },
    "scripts": {
        "bundle": "browserify -r mqtt -s mqtt | uglifyjs --screw-ie8 > public/mqtt.js",
        "ci": "mocha --recursive --bail --watch test",
        "coverage": "rm -rf coverage; istanbul cover _mocha -- --recursive --reporter spec --bail",
        "jshint-lib": "jshint lib",
        "jshint-test": "jshint test",
        "prepublish": "npm run bundle",
        "publish-coverage": "(cat coverage/lcov.info | coveralls)",
        "start": "./bin/mosca -v | bunyan",
        "test": "mocha --recursive --bail --reporter spec test 2>&1"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
