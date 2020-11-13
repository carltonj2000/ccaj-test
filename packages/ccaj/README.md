ccaj
====

Carlton&#39;s Scripts

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/ccaj.svg)](https://npmjs.org/package/ccaj)
[![Downloads/week](https://img.shields.io/npm/dw/ccaj.svg)](https://npmjs.org/package/ccaj)
[![License](https://img.shields.io/npm/l/ccaj.svg)](https://github.com/carltonj2000/ccaj/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @carltonj2000/ccaj
$ ccaj COMMAND
running command...
$ ccaj (-v|--version|version)
@carltonj2000/ccaj/0.0.2 linux-x64 node-v14.5.0
$ ccaj --help [COMMAND]
USAGE
  $ ccaj COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`ccaj hello [FILE]`](#ccaj-hello-file)
* [`ccaj help [COMMAND]`](#ccaj-help-command)

## `ccaj hello [FILE]`

describe the command here

```
USAGE
  $ ccaj hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ ccaj hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/carltonj2000/ccaj/blob/v0.0.2/src/commands/hello.ts)_

## `ccaj help [COMMAND]`

display help for ccaj

```
USAGE
  $ ccaj help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->
