# npmtest-youtube-api

#### basic test coverage for  [youtube-api (v2.0.8)](https://github.com/IonicaBizau/youtube-api)  [![npm package](https://img.shields.io/npm/v/npmtest-youtube-api.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-youtube-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-youtube-api.svg)](https://travis-ci.org/npmtest/node-npmtest-youtube-api)

#### A Node.JS module, which provides an object oriented wrapper for the Youtube v3 API.

[![NPM](https://nodei.co/npm/youtube-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/youtube-api)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-youtube-api/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-youtube-api/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-youtube-api/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-youtube-api/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-youtube-api/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-youtube-api/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-youtube-api/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-youtube-api/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-youtube-api/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-youtube-api/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-youtube-api/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-youtube-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-youtube-api/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-youtube-api/build/test-report.html](https://npmtest.github.io/node-npmtest-youtube-api/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-youtube-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-youtube-api/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-youtube-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-youtube-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-youtube-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-youtube-api/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-youtube-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-youtube-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ionică Bizău",
        "url": "https://ionicabizau.net"
    },
    "blah": {
        "show_jsdocs": false,
        "documentation": [
            "The [official Youtube documentation](https://developers.google.com/youtube/v3/docs/) is a very useful resource.",
            {
                "ul": [
                    "[Activities](https://developers.google.com/youtube/v3/docs/activities)",
                    "[ChannelBanners](https://developers.google.com/youtube/v3/docs/channelBanners)",
                    "[Channels](https://developers.google.com/youtube/v3/docs/channels)",
                    "[GuideCategories](https://developers.google.com/youtube/v3/docs/guideCategories)",
                    "[PlaylistItems](https://developers.google.com/youtube/v3/docs/playlistItems)",
                    "[Playlists](https://developers.google.com/youtube/v3/docs/playlists)",
                    "[Search](https://developers.google.com/youtube/v3/docs/search)",
                    "[Subscriptions](https://developers.google.com/youtube/v3/docs/subscriptions)",
                    "[Thumbnails](https://developers.google.com/youtube/v3/docs/thumbnails)",
                    "[VideoCategories](https://developers.google.com/youtube/v3/docs/videoCategories)",
                    "[Videos](https://developers.google.com/youtube/v3/docs/videos)"
                ]
            },
            "If you have any questions, please [ask them on **Stack Overflow**](https://stackoverflow.com/questions/ask) and eventually [open an issue](https://github.com/IonicaBizau/youtube-api/issues/new) and link your question there.",
            "",
            {
                "h3": "Authentication"
            },
            "",
            {
                "h4": "OAuth (Access Token)"
            },
            {
                "code": {
                    "language": "js",
                    "content": [
                        "Youtube.authenticate({",
                        "    type: \"oauth\"",
                        "  , token: \"your access token\"",
                        "});"
                    ]
                }
            },
            {
                "h4": "OAuth (Refresh Token)"
            },
            {
                "code": {
                    "language": "js",
                    "content": [
                        "Youtube.authenticate({",
                        "    type: \"oauth\"",
                        "  , refresh_token: \"your refresh token\"",
                        "  , client_id: \"your client id\"",
                        "  , client_secret: \"your client secret\"",
                        "  , redirect_url: \"your refresh url\"",
                        "});"
                    ]
                }
            },
            {
                "h4": "Server Key"
            },
            "Only for requests that don't require [user authorization](https://developers.google.com/youtube/v3/guides/authentication) (certain list operations)",
            {
                "code": {
                    "language": "js",
                    "content": [
                        "Youtube.authenticate({",
                        "    type: \"key\"",
                        "  , key: \"your server key\"",
                        "});"
                    ]
                }
            }
        ]
    },
    "bugs": {
        "url": "https://github.com/IonicaBizau/youtube-api/issues"
    },
    "contributors": [
        {
            "name": "Ionică Bizău"
        },
        {
            "name": "Adam",
            "url": "brutalhonesty"
        },
        {
            "name": "Michael Scharl"
        },
        {
            "name": "Vels",
            "url": "velsa"
        },
        {
            "name": "Rasmus Karlsson"
        },
        {
            "name": "Brad Oyler"
        }
    ],
    "dependencies": {
        "googleapis": "^5.2.1"
    },
    "description": "A Node.JS module, which provides an object oriented wrapper for the Youtube v3 API.",
    "devDependencies": {
        "bug-killer": "^4.2.2",
        "lien": "^1.0.1",
        "opn": "^4.0.1",
        "pretty-bytes": "^3.0.1",
        "r-json": "^1.2.2"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "6f9ac0b3c4cfe110b100330ea404aa0ad885501f",
        "tarball": "https://registry.npmjs.org/youtube-api/-/youtube-api-2.0.8.tgz"
    },
    "files": [
        "bin/",
        "app/",
        "lib/",
        "dist/",
        "src/",
        "scripts/",
        "resources/",
        "menu/",
        "cli.js",
        "index.js"
    ],
    "gitHead": "427d667f461c1121a83b041c9e3ed08c9b6f8f17",
    "homepage": "https://github.com/IonicaBizau/youtube-api",
    "keywords": [
        "youtube",
        "api",
        "v3",
        "node"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "ionicabizau"
        }
    ],
    "name": "youtube-api",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/IonicaBizau/youtube-api.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "2.0.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
