# npmdoc-cloudinary

#### basic api documentation for  [cloudinary (v1.8.0)](http://cloudinary.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-cloudinary.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cloudinary) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cloudinary.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cloudinary)

#### Cloudinary NPM for node.js integration

[![NPM](https://nodei.co/npm/cloudinary.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cloudinary)

- [https://npmdoc.github.io/node-npmdoc-cloudinary/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cloudinary/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cloudinary/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cloudinary/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cloudinary/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cloudinary/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cloudinary"
    },
    "browserify": {
        "transform": [
            "coffeeify"
        ]
    },
    "bugs": {
        "url": "https://github.com/cloudinary/cloudinary_npm/issues"
    },
    "dependencies": {
        "lodash": "3.10.x",
        "q": "1.4.x"
    },
    "description": "Cloudinary NPM for node.js integration",
    "devDependencies": {
        "coffee-script": "^1.10.0",
        "dotenv": "1.x",
        "expect.js": "0.3.x",
        "jsdom": "^9.5.0",
        "jsdom-global": "^2.1.0",
        "mocha": "2.3.x",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "52e7a18dfe3c0ece01abc71341be95d0ea198d85",
        "tarball": "https://registry.npmjs.org/cloudinary/-/cloudinary-1.8.0.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "6896efff8d5ed5c0e085d47aa637c9b77d5a373b",
    "homepage": "http://cloudinary.com",
    "license": "MIT",
    "main": "cloudinary.js",
    "maintainers": [
        {
            "name": "cloudinary"
        }
    ],
    "name": "cloudinary",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cloudinary/cloudinary_npm.git"
    },
    "scripts": {
        "compile": "coffee --map -o lib -c src",
        "prepublish": "npm run compile",
        "pretest": "npm run compile",
        "test": "mocha -R spec --recursive test/",
        "watch": "coffee --watch --map -o lib -c src"
    },
    "version": "1.8.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
