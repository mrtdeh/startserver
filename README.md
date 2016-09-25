# startserver

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/startserver.svg?style=flat-square
[npm-url]: https://npmjs.org/package/startserver
[travis-image]: https://img.shields.io/travis/xudafeng/startserver.svg?style=flat-square
[travis-url]: https://travis-ci.org/xudafeng/startserver
[coveralls-image]: https://img.shields.io/coveralls/xudafeng/startserver.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/xudafeng/startserver?branch=master
[node-image]: https://img.shields.io/badge/node.js-%3E=_4-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/startserver.svg?style=flat-square
[download-url]: https://npmjs.org/package/startserver

> Yet another http server.

## Installation

### Node requirement

\>= 0.10.x

### Install from npm

```shell
$ npm i startserver -g
```

Use it for generator support, add this alias to your `.bash_profile`:

```
alias node='node --harmony'
```

Or you'd better use [io.js](https://iojs.org/cn/index.html) as an alternative.

## Quick Start

```shell
$ startserver
```

It also can be use it like this:

```shell
$ startserver 6789
```

There are more shorter alias for it:

```shell
$ ss
```

## Features

### Server Everywhere

Run it at every directory under the root.

  * Automatic detection of unoccupied port.

### Slider Revolution

Generate slider with `README.md` file or other markdown file.

  * Suppor a inverse color style.
  * Double click for temporary modifications, again to restore.
  * Normal to read makedown.
  * Highlight for your code block.
  * Thumbnail mode provided.

### Others

  * Generator support and compatible runtime.
  * Original javascript source code.

## Commands

#### plugins

show plugin list

#### generate

```shell
$ startsever generate README.md
```
generate static slide file to markdown [[sample]](https://rawgit.com/xudafeng/startserver/master/README.md.html)

## Plugins

![logo](https://avatars3.githubusercontent.com/u/9607546?v=3&s=100)

[plugins list](https://github.com/startserver)

## Options

#### -s, --silent

start http server without opening browser

#### -m, --markdown

auto parse and render markdown file

#### -f, --pdf

render markdown file with pdf style

#### -p, --port

port to use (8080 default)

#### -d, --disable

disable default index router

#### -v, --version

output version infomation

## Help

```shell
$ startserver -h
```
## License

The MIT License (MIT)

Copyright (c) 2013 xdf
