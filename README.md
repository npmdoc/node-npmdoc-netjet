# api documentation for  [netjet (v1.1.3)](https://github.com/cloudflare/netjet#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-netjet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-netjet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-netjet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-netjet)
#### Express middleware to generate preload headers

[![NPM](https://nodei.co/npm/netjet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/netjet)

- [https://npmdoc.github.io/node-npmdoc-netjet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-netjet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-netjet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-netjet/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-netjet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-netjet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Terin Stock",
        "url": "https://terinstock.com/"
    },
    "bugs": {
        "url": "https://github.com/cloudflare/netjet/issues"
    },
    "dependencies": {
        "bl": "^1.0.1",
        "hijackresponse": "^2.0.0",
        "lodash.defaults": "^4.0.0",
        "lodash.unescape": "^4.0.0",
        "lru-cache": "^4.0.0",
        "posthtml": "^0.9.0"
    },
    "description": "Express middleware to generate preload headers",
    "devDependencies": {
        "assume": "^1.3.1",
        "coveralls": "^2.11.6",
        "detour": "^1.3.0",
        "istanbul": "^0.4.2",
        "mocha": "^3.0.0",
        "supertest": "^2.0.0",
        "supertest-as-promised": "^4.0.0",
        "testdouble": "^1.0.0",
        "xo": "^0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5c4254b971362245afdf5f94d8f524bee91d7d5a",
        "tarball": "https://registry.npmjs.org/netjet/-/netjet-1.1.3.tgz"
    },
    "files": [
        "index.js",
        "posthtml-preload.js"
    ],
    "gitHead": "40c6aa489ab747bb1f65fb335355648fddeec9f1",
    "homepage": "https://github.com/cloudflare/netjet#readme",
    "keywords": [
        "express",
        "middleware",
        "link",
        "preload"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "terinjokes"
        }
    ],
    "name": "netjet",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cloudflare/netjet.git"
    },
    "scripts": {
        "coverage": "cat ./coverage/lcov.info | coveralls",
        "test": "xo && istanbul cover -- _mocha --check-leaks --reporter spec"
    },
    "version": "1.1.3",
    "xo": {
        "space": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
