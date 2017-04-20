# npmtest-s3-upload-stream

#### basic test coverage for  [s3-upload-stream (v1.0.7)](https://github.com/nathanpeck/s3-upload-stream)  [![npm package](https://img.shields.io/npm/v/npmtest-s3-upload-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-s3-upload-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-s3-upload-stream.svg)](https://travis-ci.org/npmtest/node-npmtest-s3-upload-stream)

#### Writeable stream for uploading content of unknown size to S3 via the multipart API.

[![NPM](https://nodei.co/npm/s3-upload-stream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/s3-upload-stream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-s3-upload-stream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-s3-upload-stream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-s3-upload-stream/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-s3-upload-stream/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-s3-upload-stream/build/test-report.html](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-s3-upload-stream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-s3-upload-stream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-s3-upload-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-s3-upload-stream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-s3-upload-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Peck"
    },
    "bugs": {
        "url": "https://github.com/nathanpeck/s3-upload-stream/issues"
    },
    "dependencies": {},
    "description": "Writeable stream for uploading content of unknown size to S3 via the multipart API.",
    "devDependencies": {
        "aws-sdk": "2.0.17",
        "chai": "1.8.1",
        "mocha": "1.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e3f80253141c569f105a62aa50ca9b45760e481d",
        "tarball": "https://registry.npmjs.org/s3-upload-stream/-/s3-upload-stream-1.0.7.tgz"
    },
    "engines": {
        "node": ">=0.10.x"
    },
    "gitHead": "d410c27148b30c14de2e97d61d42971b8c37f5af",
    "homepage": "https://github.com/nathanpeck/s3-upload-stream",
    "keywords": [
        "aws",
        "s3",
        "upload",
        "pipe",
        "stream"
    ],
    "license": "MIT",
    "main": "./lib/s3-upload-stream.js",
    "maintainers": [
        {
            "name": "nathanpeck"
        }
    ],
    "name": "s3-upload-stream",
    "optionalDependencies": {},
    "peerDependencies": {
        "aws-sdk": "2.x"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/nathanpeck/s3-upload-stream.git"
    },
    "scripts": {
        "test": "mocha -R spec -s 100 ./tests/test.js"
    },
    "version": "1.0.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
