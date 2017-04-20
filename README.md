# npmdoc-homebridge-server

#### api documentation for  homebridge-server (v1.0.24)  [![npm package](https://img.shields.io/npm/v/npmdoc-homebridge-server.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-homebridge-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-homebridge-server.svg)](https://travis-ci.org/npmdoc/node-npmdoc-homebridge-server)

#### Server plugin for homebridge: https://github.com/nfarina/homebridge

[![NPM](https://nodei.co/npm/homebridge-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/homebridge-server)

- [https://npmdoc.github.io/node-npmdoc-homebridge-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-homebridge-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-homebridge-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-homebridge-server/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-homebridge-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-homebridge-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "homebridge-server",
    "version": "1.0.24",
    "description": "Server plugin for homebridge: https://github.com/nfarina/homebridge",
    "license": "ISC",
    "keywords": [
        "homebridge-plugin"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/gismo141/homebridge-server.git"
    },
    "bugs": {
        "url": "http://github.com/gismo141/homebridge-server/issues"
    },
    "engines": {
        "node": ">=0.12.0",
        "homebridge": ">=0.2.0"
    },
    "dependencies": {
        "homebridge": ">=0.4.9"
    },
    "scripts": {
        "test": "homebridge -U ~/.homebridge -P . > /dev/null 2>&1 & sleep 10; ( curl -Is http://127.0.0.1:8765/remove | head -1 ); kill $!"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
