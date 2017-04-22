# npmdoc-gulp-file-sync

#### api documentation for  [gulp-file-sync (v1.0.7)](https://github.com/kayo5994/gulp-file-sync#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-file-sync.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-file-sync) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-file-sync.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-file-sync)

#### Sync file It keeps your files synced between two directory. In other words, any change of files in one directory will automatically take place in another one.

[![NPM](https://nodei.co/npm/gulp-file-sync.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-file-sync)

- [https://npmdoc.github.io/node-npmdoc-gulp-file-sync/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-file-sync/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-file-sync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-file-sync/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-file-sync/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-file-sync/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kayo Lee"
    },
    "bugs": {
        "url": "https://github.com/kayo5994/gulp-file-sync/issues"
    },
    "dependencies": {
        "crc": "^3.4.4",
        "fs-extra": "^2.0.0",
        "gulp-util": "^3.0.8"
    },
    "description": "Sync file It keeps your files synced between two directory. In other words, any change of files in one directory will automatically take place in another one.",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.16",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "96ef6458980ecdaceffdcaa96b878f22748b3852",
        "tarball": "https://registry.npmjs.org/gulp-file-sync/-/gulp-file-sync-1.0.7.tgz"
    },
    "gitHead": "5d2eb98e8f1e71dc2f4e735e0b06189c7e07fb4f",
    "homepage": "https://github.com/kayo5994/gulp-file-sync#readme",
    "keywords": [
        "sync",
        "Synchronize",
        "file",
        "manage",
        "gulpplugin",
        "gulpplugin",
        "gulpfriendly",
        "gulpfriendly"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kayo5994"
        }
    ],
    "name": "gulp-file-sync",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kayo5994/gulp-file-sync.git"
    },
    "scripts": {
        "cov": "istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "1.0.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
