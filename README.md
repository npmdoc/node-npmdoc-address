# npmdoc-address

#### basic api documentation for  [address (v1.0.1)](https://github.com/node-modules/address#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-address.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-address) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-address.svg)](https://travis-ci.org/npmdoc/node-npmdoc-address)

#### Get current machine IP, MAC and DNS servers.

[![NPM](https://nodei.co/npm/address.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/address)

- [https://npmdoc.github.io/node-npmdoc-address/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-address/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-address/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-address/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-address/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-address/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2"
    },
    "bugs": {
        "url": "https://github.com/node-modules/address/issues"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "url": "http://fengmk2.com"
        },
        {
            "name": "alsotang",
            "url": "https://github.com/alsotang"
        }
    ],
    "dependencies": {},
    "description": "Get current machine IP, MAC and DNS servers.",
    "devDependencies": {
        "contributors": "*",
        "istanbul": "*",
        "matcha": "*",
        "mm": "*",
        "mocha": "*",
        "pedding": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "363f5d3f2be26d0655d8afd5a9562e4fc2194537",
        "tarball": "https://registry.npmjs.org/address/-/address-1.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "fc3536a8f2a3862d3c8066178b3f7d60483192cc",
    "homepage": "https://github.com/node-modules/address#readme",
    "keywords": [
        "address",
        "ip",
        "ipv4",
        "mac"
    ],
    "license": "MIT",
    "main": "lib/address.js",
    "maintainers": [
        {
            "name": "fengmk2"
        }
    ],
    "name": "address",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/address.git"
    },
    "scripts": {
        "autod": "autod -w --prefix '^'",
        "benchmark": "matcha",
        "cnpm": "npm install --registry=https://registry.npm.taobao.org",
        "contributors": "contributors -f plain -o AUTHORS",
        "test": "mocha --check-leaks -R spec -t 5000 test/*.test.js",
        "test-cov": "istanbul cover node_modules/.bin/_mocha -- --check-leaks -t 5000 test/*.test.js",
        "test-travis": "istanbul cover node_modules/.bin/_mocha --report lcovonly -- --check-leaks -t 5000 test/*.test.js"
    },
    "version": "1.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
