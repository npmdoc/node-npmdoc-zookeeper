# npmdoc-zookeeper

#### api documentation for  zookeeper (v3.4.9-3)  [![npm package](https://img.shields.io/npm/v/npmdoc-zookeeper.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-zookeeper) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-zookeeper.svg)](https://travis-ci.org/npmdoc/node-npmdoc-zookeeper)

#### apache zookeeper client (zookeeper async API >= 3.4.0)

[![NPM](https://nodei.co/npm/zookeeper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/zookeeper)

- [https://npmdoc.github.io/node-npmdoc-zookeeper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-zookeeper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zookeeper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zookeeper/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-zookeeper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-zookeeper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "zookeeper",
    "description": "apache zookeeper client (zookeeper async API >= 3.4.0)",
    "version": "3.4.9-3",
    "author": "Yuri Finkelstein <yurif2003@yahoo.com>",
    "contributors": [
        "Yuri Finkelstein <yurif2003@yahoo.com>",
        "Woody Anderson <woody.anderson@gmail.com>",
        "Mark Cavage <mcavage@gmail.com>",
        "Dave Dopson <ddopson@gmail.com>",
        "David Trejo <david.daniel.trejo@gmail.com>",
        "Pooya Karimian <pkarimian@sencha.com>",
        "Jakub Lekstan <kuebzky@gmail.com>",
        "Matt Lavin <matt.lavin@gmail.com>",
        "Roy Cheng <roy.b.cheng@newegg.com>"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/yfinkelstein/node-zookeeper"
    },
    "keywords": [
        "apache",
        "zookeeper",
        "client"
    ],
    "dependencies": {
        "async": "~2.1.4",
        "nan": "~2.5.0",
        "lodash": "~4.17.2"
    },
    "devDependencies": {
        "log4js": "~1.0.1",
        "webworker": ">=0.8.4"
    },
    "main": "lib/index",
    "scripts": {
        "build": "node-gyp configure build",
        "test": "pushd test; ./test; popd",
        "prepublish": "./scripts/prepublish.sh"
    },
    "engines": {
        "node": ">=0.10"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
