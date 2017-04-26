# npmdoc-redlock

#### basic api documentation for  [redlock (v2.1.0)](https://github.com/mike-marcacci/node-redlock)  [![npm package](https://img.shields.io/npm/v/npmdoc-redlock.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-redlock) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redlock.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redlock)

#### A node.js redlock implementation for distributed redis locks

[![NPM](https://nodei.co/npm/redlock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redlock)

- [https://npmdoc.github.io/node-npmdoc-redlock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redlock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redlock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redlock/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redlock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redlock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Marcacci"
    },
    "bugs": {
        "url": "https://github.com/mike-marcacci/node-redlock/issues"
    },
    "config": {
        "blanket": {
            "pattern": [
                "redlock.js"
            ]
        }
    },
    "dependencies": {
        "bluebird": "^3.3.3"
    },
    "description": "A node.js redlock implementation for distributed redis locks",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.8",
        "ioredis": "^1.15.1",
        "istanbul": "^0.4.2",
        "mocha": "^2.4.5",
        "redis": "^2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "f00ddff6b74069dfbf4d2fd11ed8104475bfef76",
        "tarball": "https://registry.npmjs.org/redlock/-/redlock-2.1.0.tgz"
    },
    "gitHead": "95e364b44ffde08f25313ebc58c6f1b2906e6297",
    "homepage": "https://github.com/mike-marcacci/node-redlock",
    "keywords": [
        "nodejs",
        "iojs",
        "redlock",
        "distributed",
        "lock",
        "redis"
    ],
    "license": "MIT",
    "main": "redlock.js",
    "maintainers": [
        {
            "name": "mike-marcacci"
        }
    ],
    "name": "redlock",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mike-marcacci/node-redlock.git"
    },
    "scripts": {
        "test": "istanbul cover mocha",
        "test-ci": "istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | coveralls"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
