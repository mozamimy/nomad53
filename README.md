# nomad53

## Overview

Register an IP address that assigned your computer to AWS Route 53.

## Usage

You shoud give AWS credentials because this script uses AWS CLI.

```
$ nomad53 [adapter] [Hosted zone ID] [FQDN]
```

For instance,

```
$ envchain aws-gokatei nomad53 en5 ZB3J3CGDM0KPR me.mozami.me
```

## LICENSE

All code snippets are licensed under CC0 unless otherwise specified.
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
