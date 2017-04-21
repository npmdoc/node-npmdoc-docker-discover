# npmdoc-docker-discover

#### api documentation for  docker-discover (v0.4.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-docker-discover.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-docker-discover) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-docker-discover.svg)](https://travis-ci.org/npmdoc/node-npmdoc-docker-discover)

#### Service Discovery for Docker

[![NPM](https://nodei.co/npm/docker-discover.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/docker-discover)

- [https://npmdoc.github.io/node-npmdoc-docker-discover/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-docker-discover/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-docker-discover/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-docker-discover/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-docker-discover/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-docker-discover/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "docker-discover",
    "version": "0.4.1",
    "description": "Service Discovery for Docker",
    "keywords": [
        "docker",
        "etcd",
        "totem",
        "service",
        "discovery"
    ],
    "main": "index.js",
    "bin": {
        "discover": "index.js"
    },
    "dependencies": {
        "async": "*",
        "request": "*",
        "winston": "*",
        "nconf": "*",
        "docker.io": "*",
        "node-etcd": "*",
        "set": "*"
    },
    "devDependencies": {
        "chai": "*",
        "rewire": "*",
        "grunt": "*",
        "grunt-contrib-jshint": "*",
        "grunt-mocha-cov": "*",
        "mocha-term-cov-reporter": "*",
        "grunt-cli": "*",
        "grunt-shell": "*"
    },
    "scripts": {
        "test": "./node_modules/bin/grunt test",
        "blanket": {
            "pattern": [
                "discover/lib",
                "discover/index"
            ]
        }
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/totem/discover.git"
    },
    "author": "Mike Moulton <mike@meltmedia.com>",
    "bugs": {
        "url": "https://github.com/totem/discover/issues"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
