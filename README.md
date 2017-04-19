# npmtest-grunt-contrib-qunit

#### test coverage for  [grunt-contrib-qunit (v2.0.0)](https://github.com/gruntjs/grunt-contrib-qunit#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-contrib-qunit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-contrib-qunit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-contrib-qunit.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-contrib-qunit)

#### Run QUnit unit tests in a headless PhantomJS instance

[![NPM](https://nodei.co/npm/grunt-contrib-qunit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-contrib-qunit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-contrib-qunit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-contrib-qunit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-contrib-qunit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-contrib-qunit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-contrib-qunit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-contrib-qunit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-contrib-qunit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "appveyor_id": "3vd43779joyj6qji",
    "author": {
        "name": "Grunt Team",
        "url": "http://gruntjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gruntjs/grunt-contrib-qunit/issues"
    },
    "contributors": [
        {
            "name": "\"Cowboy\" Ben Alman",
            "url": "http://benalman.com/"
        },
        {
            "name": "Tyler Kellen",
            "url": "http://goingslowly.com/"
        },
        {
            "name": "Jörn Zaefferer",
            "url": "http://bassistance.de/"
        },
        {
            "name": "Kyle Robinson Young",
            "url": "http://dontkry.com/"
        },
        {
            "name": "Vlad Filippov",
            "url": "http://vladfilippov.com/"
        },
        {
            "name": "Jarrod Overson",
            "url": "http://jarrodoverson.com/"
        },
        {
            "name": "Thanasis Polychronakis",
            "url": "http://thanpol.as"
        },
        {
            "name": "Richard D. Worth"
        },
        {
            "name": "Brian Chirls"
        },
        {
            "name": "Thomas Omans",
            "url": "http://samesake.com/"
        },
        {
            "name": "Eliazer Braun"
        },
        {
            "name": "Lars Thorup"
        },
        {
            "name": "Nick Weingartner"
        },
        {
            "name": "Schalk Neethling"
        },
        {
            "name": "Shaker Islam"
        },
        {
            "name": "Stephen Brandwood"
        },
        {
            "name": "Mark Bailie",
            "url": "http://markbailie.co.uk"
        },
        {
            "name": "Sam Kirkpatrick"
        }
    ],
    "dependencies": {
        "grunt-lib-phantomjs": "^1.0.0"
    },
    "description": "Run QUnit unit tests in a headless PhantomJS instance",
    "devDependencies": {
        "difflet": "^1.0.1",
        "grunt": "^1.0.1",
        "grunt-contrib-connect": "^1.0.0",
        "grunt-contrib-internal": "^1.1.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-shell": "^1.3.0",
        "qunitjs": "^2.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "54a51b4b2c84fee62c3b7e00145c928d1ec2b7ec",
        "tarball": "https://registry.npmjs.org/grunt-contrib-qunit/-/grunt-contrib-qunit-2.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "tasks",
        "phantomjs"
    ],
    "gitHead": "b9522f40a518fcba2d06032512c882738d496256",
    "homepage": "https://github.com/gruntjs/grunt-contrib-qunit#readme",
    "keywords": [
        "gruntplugin"
    ],
    "license": "MIT",
    "main": "tasks/qunit.js",
    "maintainers": [
        {
            "name": "arkni"
        },
        {
            "name": "cowboy"
        },
        {
            "name": "jmeas"
        },
        {
            "name": "jsoverson"
        },
        {
            "name": "jzaefferer"
        },
        {
            "name": "leobalter"
        },
        {
            "name": "shama"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "tkellen"
        },
        {
            "name": "vladikoff"
        }
    ],
    "name": "grunt-contrib-qunit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gruntjs/grunt-contrib-qunit.git"
    },
    "scripts": {
        "test": "grunt test --stack"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
