oclif-starter
=============



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/oclif-starter.svg)](https://npmjs.org/package/oclif-starter)
[![Downloads/week](https://img.shields.io/npm/dw/oclif-starter.svg)](https://npmjs.org/package/oclif-starter)
[![License](https://img.shields.io/npm/l/oclif-starter.svg)](https://github.com/BatuhanW/oclif-starter/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g oclif-starter
$ oclif-starter COMMAND
running command...
$ oclif-starter (-v|--version|version)
oclif-starter/0.1.0 darwin-x64 node-v12.22.1
$ oclif-starter --help [COMMAND]
USAGE
  $ oclif-starter COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`oclif-starter hello [FILE]`](#oclif-starter-hello-file)
* [`oclif-starter help [COMMAND]`](#oclif-starter-help-command)

## `oclif-starter hello [FILE]`

describe the command here

```
USAGE
  $ oclif-starter hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ oclif-starter hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/BatuhanW/oclif-starter/blob/v0.1.0/src/commands/hello.ts)_

## `oclif-starter help [COMMAND]`

display help for oclif-starter

```
USAGE
  $ oclif-starter help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
