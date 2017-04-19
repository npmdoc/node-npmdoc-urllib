# npmdoc-urllib

#### api documentation for  [urllib (v2.22.0)](http://github.com/node-modules/urllib)  [![npm package](https://img.shields.io/npm/v/npmdoc-urllib.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-urllib) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-urllib.svg)](https://travis-ci.org/npmdoc/node-npmdoc-urllib)

#### Help in opening URLs (mostly HTTP) in a complex world — basic and digest authentication, redirections, cookies and more.

[![NPM](https://nodei.co/npm/urllib.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/urllib)

- [https://npmdoc.github.io/node-npmdoc-urllib/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-urllib/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-urllib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-urllib/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-urllib/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-urllib/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2",
        "url": "https://fengmk2.com"
    },
    "bugs": {
        "url": "https://github.com/node-modules/urllib/issues"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "url": "http://fengmk2.com"
        },
        {
            "name": "aleafs",
            "url": "https://github.com/aleafs"
        },
        {
            "name": "Jackson Tian",
            "url": "https://github.com/JacksonTian"
        },
        {
            "name": "ibigbug",
            "url": "https://github.com/ibigbug"
        },
        {
            "name": "XiNGRZ",
            "url": "https://github.com/XiNGRZ"
        },
        {
            "name": "dead_horse",
            "url": "http://deadhorse.me/"
        },
        {
            "name": "coderhaoxin",
            "url": "https://github.com/coderhaoxin"
        },
        {
            "name": "alsotang",
            "url": "https://github.com/alsotang"
        },
        {
            "name": "Jonathan Dahan",
            "url": "https://github.com/jedahan"
        },
        {
            "name": "popomore",
            "url": "https://github.com/popomore"
        },
        {
            "name": "fishbar",
            "url": "https://github.com/fishbar"
        },
        {
            "name": "coolme200",
            "url": "https://github.com/coolme200"
        },
        {
            "name": "amunu",
            "url": "https://github.com/Amunu"
        },
        {
            "name": "Yuwei Ba",
            "url": "https://github.com/ibigbug"
        }
    ],
    "dependencies": {
        "any-promise": "^1.3.0",
        "content-type": "^1.0.2",
        "debug": "^2.6.0",
        "default-user-agent": "^1.0.0",
        "digest-header": "^0.0.1",
        "ee-first": "~1.1.1",
        "humanize-ms": "^1.2.0",
        "iconv-lite": "^0.4.15",
        "qs": "^6.4.0",
        "statuses": "^1.3.1"
    },
    "description": "Help in opening URLs (mostly HTTP) in a complex world — basic and digest authentication, redirections, cookies and more.",
    "devDependencies": {
        "agentkeepalive": "^2.2.0",
        "autod": "*",
        "bluebird": "*",
        "busboy": "^0.2.14",
        "co": "*",
        "coffee": "1",
        "formstream": "^1.1.0",
        "intelli-espower-loader": "^1.0.1",
        "istanbul": "*",
        "jshint": "*",
        "mocha": "*",
        "muk": "^0.4.0",
        "pedding": "^1.1.0",
        "power-assert": "^1.4.2",
        "semver": "5",
        "tar": "^2.2.1",
        "through2": "^2.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "2965dc4ae127a6fb695b7db27d3184f17d82cb42",
        "tarball": "https://registry.npmjs.org/urllib/-/urllib-2.22.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "677e2ef90b3c0e0f26889696ca6eb88e2c4f5ded",
    "homepage": "http://github.com/node-modules/urllib",
    "keywords": [
        "urllib",
        "http",
        "urlopen",
        "curl",
        "wget",
        "request",
        "https"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "fengmk2"
        },
        {
            "name": "dead_horse"
        }
    ],
    "name": "urllib",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/urllib.git"
    },
    "scripts": {
        "autod": "autod -w --prefix '^' -t test -e examples",
        "ci": "npm run lint && npm run test-cov",
        "lint": "jshint .",
        "test": "npm run lint && mocha -R spec -t 30000 -r intelli-espower-loader test/*.test.js",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- -t 30000 -r intelli-espower-loader test/*.test.js"
    },
    "version": "2.22.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
