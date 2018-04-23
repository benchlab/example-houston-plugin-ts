# Example HOUSTON Plugin (TypeScript)
========================

[![Greenkeeper badge](https://badges.greenkeeper.io/benchlab/example-houston-plugin-ts.svg)](https://greenkeeper.io/)
[![Version](https://img.shields.io/npm/v/example-houston-plugin-ts.svg)](https://npmjs.org/package/example-houston-plugin-ts)
[![CircleCI](https://circleci.com/gh/benchlab/example-houston-plugin-ts/tree/master.svg?style=shield)](https://circleci.com/gh/benchlab/example-houston-plugin-ts/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/benchlab/example-houston-plugin-ts?branch=master&svg=true)](https://ci.appveyor.com/project/lyndon/example-houston-plugin-ts/branch/master)
[![Codecov](https://codecov.io/gh/benchlab/example-houston-plugin-ts/branch/master/graph/badge.svg)](https://codecov.io/gh/benchlab/example-houston-plugin-ts)
[![Downloads/week](https://img.shields.io/npm/dw/example-houston-plugin-ts.svg)](https://npmjs.org/package/example-houston-plugin-ts)
[![License](https://img.shields.io/npm/l/example-houston-plugin-ts.svg)](https://github.com/benchlab/example-houston-plugin-ts/blob/master/package.json)

<!-- toc -->
* [Example HOUSTON Plugin (TypeScript)](#example-houston-plugin-type-script)
* [Usage](#usage)
* [Guidances](#guidances)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g example-houston-plugin-ts
$ houston-example GUIDANCE
Communicating with Houston......
$ houston-example (-v|--version|version)
example-houston-plugin-ts/0.0.2 darwin-x64 node-v8.11.1
$ houston-example --help [GUIDANCE]
USAGE
  $ houston-example GUIDANCE
...
```
<!-- usagestop -->
# Guidances
<!-- guidances -->
* [`houston-example hello [FILE]`](#houston-example-hello-file)

## `houston-example hello [FILE]`

describe the guidance here

```
USAGE
  $ houston-example hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show HOUSTON help
  -n, --name=name  name to print

EXAMPLE
  $ lyndon-example hello
  hello world from ./src/hello.ts!
```

_See code: [src/guidances/hello.ts](https://github.com/benchlab/example-houston-plugin-ts/blob/v0.0.2/src/guidances/hello.ts)_
<!-- guidancesstop -->
