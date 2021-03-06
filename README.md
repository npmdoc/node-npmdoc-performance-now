# npmdoc-performance-now

#### api documentation for  [performance-now (v2.1.0)](https://github.com/braveg1rl/performance-now)  [![npm package](https://img.shields.io/npm/v/npmdoc-performance-now.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-performance-now) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-performance-now.svg)](https://travis-ci.org/npmdoc/node-npmdoc-performance-now)

#### Implements performance.now (based on process.hrtime).

[![NPM](https://nodei.co/npm/performance-now.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/performance-now)

- [https://npmdoc.github.io/node-npmdoc-performance-now/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-performance-now/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-performance-now/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-performance-now/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-performance-now/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-performance-now/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Braveg1rl"
    },
    "bugs": {
        "url": "https://github.com/braveg1rl/performance-now/issues"
    },
    "dependencies": {},
    "description": "Implements performance.now (based on process.hrtime).",
    "devDependencies": {
        "bluebird": "^3.4.7",
        "call-delayed": "^1.0.0",
        "chai": "^3.5.0",
        "chai-increasing": "^1.2.0",
        "coffee-script": "~1.12.2",
        "mocha": "~3.2.0",
        "pre-commit": "^1.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "6309f4e0e5fa913ec1c69307ae364b4b377c9e7b",
        "tarball": "https://registry.npmjs.org/performance-now/-/performance-now-2.1.0.tgz"
    },
    "gitHead": "107bb703494cc5a8071cdf45a87e53f248a5e0f3",
    "homepage": "https://github.com/braveg1rl/performance-now",
    "keywords": [],
    "license": "MIT",
    "main": "lib/performance-now.js",
    "maintainers": [
        {
            "name": "meryn"
        }
    ],
    "name": "performance-now",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git://github.com/braveg1rl/performance-now.git"
    },
    "scripts": {
        "build": "mkdir -p lib && rm -rf lib/* && node_modules/.bin/coffee --compile -m --output lib/ src/",
        "prepublish": "npm test",
        "pretest": "npm run build",
        "test": "mocha",
        "watch": "coffee --watch --compile --output lib/ src/"
    },
    "typings": "src/index.d.ts",
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
