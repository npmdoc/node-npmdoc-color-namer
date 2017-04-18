# npmdoc-color-namer

#### api documentation for  [color-namer (v1.1.0)](https://github.com/zeke/color-namer)  [![npm package](https://img.shields.io/npm/v/npmdoc-color-namer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-color-namer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-color-namer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-color-namer)

#### Give me a color and I'll name it.

[![NPM](https://nodei.co/npm/color-namer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/color-namer)

- [https://npmdoc.github.io/node-npmdoc-color-namer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-color-namer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-color-namer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-color-namer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-color-namer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-color-namer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zeke Sikelianos",
        "url": "http://zeke.sikelianos.com/"
    },
    "bugs": {
        "url": "https://github.com/zeke/color-namer/issues"
    },
    "dependencies": {
        "chroma-js": "~0.5.2",
        "euclidean-distance": "~0.1.0"
    },
    "description": "Give me a color and I'll name it.",
    "devDependencies": {
        "browserify": "^4.2.1",
        "mocha": "~1.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1338ba293d2288ba40cf649df28d0712f8830074",
        "tarball": "https://registry.npmjs.org/color-namer/-/color-namer-1.1.0.tgz"
    },
    "gitHead": "cc587083a29c29dfa5b4c89b95357f2fe9aae883",
    "homepage": "https://github.com/zeke/color-namer",
    "keywords": [
        "color",
        "colors",
        "names",
        "rgb",
        "hsl",
        "hsv",
        "lab",
        "search",
        "tagging",
        "image",
        "design"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "zeke"
        }
    ],
    "name": "color-namer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/zeke/color-namer.git"
    },
    "scripts": {
        "build": "browserify index.js --standalone colorNamer > dist/color-namer.js",
        "test": "mocha"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
