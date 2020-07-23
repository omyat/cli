omyat
=====

Old Man Yells At [CLOUD]

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/omyat.svg)](https://npmjs.org/package/omyat)
[![Downloads/week](https://img.shields.io/npm/dw/omyat.svg)](https://npmjs.org/package/omyat)
[![License](https://img.shields.io/npm/l/omyat.svg)](https://github.com/omyat/cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g omyat
$ omyat COMMAND
running command...
$ omyat (-v|--version|version)
omyat/0.0.0 linux-x64 node-v12.16.3
$ omyat --help [COMMAND]
USAGE
  $ omyat COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`omyat aws:iam:users:inactive`](#omyat-awsiamusersinactive)
* [`omyat hello [FILE]`](#omyat-hello-file)
* [`omyat help [COMMAND]`](#omyat-help-command)

## `omyat aws:iam:users:inactive`

Inactive IAM Users

```
USAGE
  $ omyat aws:iam:users:inactive

OPTIONS
  -c, --[no-]console
  -d, --days=days     [default: 100]
  -h, --help          show CLI help
  -v, --[no-]virtual

EXAMPLE
  $ omyat aws:iam:users:inactive
```

_See code: [@omyat/aws](https://github.com/omyat/aws/blob/v0.0.1/src/commands/aws/iam/users/inactive.ts)_

## `omyat hello [FILE]`

describe the command here

```
USAGE
  $ omyat hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ omyat hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/omyat/cli/blob/v0.0.0/src/commands/hello.ts)_

## `omyat help [COMMAND]`

display help for omyat

```
USAGE
  $ omyat help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.1.0/src/commands/help.ts)_
<!-- commandsstop -->
