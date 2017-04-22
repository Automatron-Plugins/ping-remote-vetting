# Remote Vetting plugin for Automatron to determine pingability of system

This shell script is a simple Vetting Plugin for Automatron (https://automatron.io). This plugin will determine if a specified host is pingable or not.

## Installation

Simply copy this script into the `plugins/vetting/remote/` directory.

```shell
$ cp ping.sh plugins/vetting/remote/
```

This plugin will generate the `facts['ping']` variable with a `true` or `false` value.
