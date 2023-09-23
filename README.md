# confd

This is a fork of [kelseyhightower/confd/](https://github.com/kelseyhightower/confd/) which is used in [rancher/rke-tools](https://github.com/rancher/rke-tools).

## Building

Running `make` should run the default target (`ci`), which runs all the scripts needed to built a binary and container. It uses `rancher/dapper` as build wrapper. You can run each steps separately if you want to skip some of the defaults, for example `make build`.
