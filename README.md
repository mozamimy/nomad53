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
