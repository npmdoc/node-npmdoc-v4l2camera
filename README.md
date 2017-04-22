# npmdoc-v4l2camera

#### api documentation for  [v4l2camera (v1.0.4)](https://github.com/bellbind/node-v4l2camera)  [![npm package](https://img.shields.io/npm/v/npmdoc-v4l2camera.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-v4l2camera) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-v4l2camera.svg)](https://travis-ci.org/npmdoc/node-npmdoc-v4l2camera)

#### Capturing images from USB(UVC) webcam on linux machines

[![NPM](https://nodei.co/npm/v4l2camera.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/v4l2camera)

- [https://npmdoc.github.io/node-npmdoc-v4l2camera/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-v4l2camera/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-v4l2camera/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-v4l2camera/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-v4l2camera/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-v4l2camera/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "v4l2camera",
    "version": "1.0.4",
    "description": "Capturing images from USB(UVC) webcam on linux machines",
    "keywords": [
        "linux",
        "camera",
        "native",
        "v4l2",
        "video4linux2"
    ],
    "homepage": "https://github.com/bellbind/node-v4l2camera",
    "bugs": {
        "url": "https://github.com/bellbind/node-v4l2camera/issues"
    },
    "license": "(MIT OR LGPL-3.0)",
    "author": "bellbind <bellbind@gmail.com> (http://bellbind.tumblr.com)",
    "main": "./index.js",
    "directories": {
        "example": "./examples"
    },
    "repository": {
        "type": "git",
        "url": "http://github.com/bellbind/node-v4l2camera.git"
    },
    "devDependencies": {
        "pngjs": "*",
        "jpeg-js": "*"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "scripts": {
        "test": "node test.js",
        "make-c-examples": "make -f c-examples.makefile"
    },
    "os": [
        "linux"
    ],
    "dependencies": {
        "nan": ">=2.3.0"
    },
    "contributors": [
        "Tim Cameron Ryan <id@timryan.org> (https://github.com/tcr)",
        "vird <virdvip@gmail.com> (https://github.com/vird)",
        "Lennart Kolmodin <kolmodin@gmail.com> (https://github.com/kolmodin)"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
