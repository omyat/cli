# omyat

Old Man Yells At [CLOUD]

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/omyat.svg)](https://npmjs.org/package/omyat)
[![Downloads/week](https://img.shields.io/npm/dw/omyat.svg)](https://npmjs.org/package/omyat)
[![License](https://img.shields.io/npm/l/omyat.svg)](https://github.com/omyat/cli/blob/master/package.json)

<!-- toc -->
* [omyat](#omyat)
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
omyat/0.1.0 linux-x64 node-v12.16.3
$ omyat --help [COMMAND]
USAGE
  $ omyat COMMAND
...
```
<!-- usagestop -->

# Commands

<!-- commands -->
* [`omyat aws:iam:users:inactive`](#omyat-awsiamusersinactive)
* [`omyat aws:route53:domains:expired`](#omyat-awsroute53domainsexpired)
* [`omyat aws:route53:domains:norenewal`](#omyat-awsroute53domainsnorenewal)
* [`omyat aws:route53:domains:registered`](#omyat-awsroute53domainsregistered)
* [`omyat aws:route53:domains:unlocked`](#omyat-awsroute53domainsunlocked)
* [`omyat aws:route53:zones:public`](#omyat-awsroute53zonespublic)
* [`omyat commands`](#omyat-commands)
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

_See code: [@omyat/aws](https://github.com/omyat/aws/blob/v0.1.0/src/commands/aws/iam/users/inactive.ts)_

## `omyat aws:route53:domains:expired`

Domains which have expired

```
USAGE
  $ omyat aws:route53:domains:expired

OPTIONS
  -h, --help  show CLI help

EXAMPLE
  $ omyat aws:route53:domains:expired
```

_See code: [@omyat/aws](https://github.com/omyat/aws/blob/v0.1.0/src/commands/aws/route53/domains/expired.ts)_

## `omyat aws:route53:domains:norenewal`

Domains with auto renewal disabled

```
USAGE
  $ omyat aws:route53:domains:norenewal

OPTIONS
  -h, --help  show CLI help

EXAMPLE
  $ omyat aws:route53:domains:norenewal
```

_See code: [@omyat/aws](https://github.com/omyat/aws/blob/v0.1.0/src/commands/aws/route53/domains/norenewal.ts)_

## `omyat aws:route53:domains:registered`

Registered domains

```
USAGE
  $ omyat aws:route53:domains:registered

OPTIONS
  -h, --help  show CLI help

EXAMPLE
  $ omyat aws:route53:domains:registered
```

_See code: [@omyat/aws](https://github.com/omyat/aws/blob/v0.1.0/src/commands/aws/route53/domains/registered.ts)_

## `omyat aws:route53:domains:unlocked`

Domains with transfer locked disabled

```
USAGE
  $ omyat aws:route53:domains:unlocked

OPTIONS
  -h, --help  show CLI help

EXAMPLE
  $ omyat aws:route53:domains:unlocked
```

_See code: [@omyat/aws](https://github.com/omyat/aws/blob/v0.1.0/src/commands/aws/route53/domains/unlocked.ts)_

## `omyat aws:route53:zones:public`

Public hosted zones

```
USAGE
  $ omyat aws:route53:zones:public

OPTIONS
  -h, --help  show CLI help

EXAMPLE
  $ omyat aws:route53:zones:public
```

_See code: [@omyat/aws](https://github.com/omyat/aws/blob/v0.1.0/src/commands/aws/route53/zones/public.ts)_

## `omyat commands`

list all the commands

```
USAGE
  $ omyat commands

OPTIONS
  -h, --help              show CLI help
  -j, --json              display unfiltered api data in json format
  -x, --extended          show extra columns
  --columns=columns       only show provided columns (comma-separated)
  --csv                   output is csv format [alias: --output=csv]
  --filter=filter         filter property by partial string matching, ex: name=foo
  --hidden                show hidden commands
  --no-header             hide table header from output
  --no-truncate           do not truncate output to fit screen
  --output=csv|json|yaml  output in a more machine friendly format
  --sort=sort             property to sort by (prepend '-' for descending)
```

_See code: [@oclif/plugin-commands](https://github.com/oclif/plugin-commands/blob/v1.3.0/src/commands/commands.ts)_

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
