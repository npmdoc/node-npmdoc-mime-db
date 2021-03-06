# npmdoc-mime-db

#### api documentation for  [mime-db (v1.27.0)](https://github.com/jshttp/mime-db#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-mime-db.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mime-db) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mime-db.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mime-db)

#### Media Type Database

[![NPM](https://nodei.co/npm/mime-db.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mime-db)

- [https://npmdoc.github.io/node-npmdoc-mime-db/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mime-db/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mime-db/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mime-db/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mime-db/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mime-db/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/mime-db/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        },
        {
            "name": "Robert Kieffer",
            "url": "http://github.com/broofa"
        }
    ],
    "dependencies": {},
    "description": "Media Type Database",
    "devDependencies": {
        "bluebird": "3.5.0",
        "co": "4.6.0",
        "cogent": "1.0.1",
        "csv-parse": "1.2.0",
        "eslint": "3.17.1",
        "eslint-config-standard": "7.0.1",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "gnode": "0.1.2",
        "istanbul": "0.4.5",
        "mocha": "1.21.5",
        "raw-body": "2.2.0",
        "stream-to-array": "2.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "820f572296bbd20ec25ed55e5b5de869e5436eb1",
        "tarball": "https://registry.npmjs.org/mime-db/-/mime-db-1.27.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "README.md",
        "db.json",
        "index.js"
    ],
    "gitHead": "c232c21378647dfbb7762410c7b025a47f114b94",
    "homepage": "https://github.com/jshttp/mime-db#readme",
    "keywords": [
        "mime",
        "db",
        "type",
        "types",
        "database",
        "charset",
        "charsets"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "mime-db",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/mime-db.git"
    },
    "scripts": {
        "build": "node scripts/build",
        "fetch": "gnode scripts/fetch-apache && gnode scripts/fetch-iana && gnode scripts/fetch-nginx",
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "update": "npm run fetch && npm run build"
    },
    "version": "1.27.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
