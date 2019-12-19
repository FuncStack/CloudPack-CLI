CloudPack-CLI
=============

The CLI installer for CloudPack

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/CloudPack-CLI.svg)](https://npmjs.org/package/CloudPack-CLI)
[![Downloads/week](https://img.shields.io/npm/dw/CloudPack-CLI.svg)](https://npmjs.org/package/CloudPack-CLI)
[![License](https://img.shields.io/npm/l/CloudPack-CLI.svg)](https://github.com/funcstack/CloudPack-CLI/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g CloudPack-CLI
$ pack COMMAND
running command...
$ pack (-v|--version|version)
CloudPack-CLI/0.0.1 darwin-x64 node-v12.13.1
$ pack --help [COMMAND]
USAGE
  $ pack COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`pack hello [FILE]`](#pack-hello-file)
* [`pack help [COMMAND]`](#pack-help-command)

## `pack hello [FILE]`

describe the command here

```
USAGE
  $ pack hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ pack hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/funcstack/CloudPack-CLI/blob/v0.0.1/src/commands/hello.ts)_

## `pack help [COMMAND]`

display help for pack

```
USAGE
  $ pack help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_
<!-- commandsstop -->
