# Aapanel

Aapanel docker compose file to customize

Update: Ubuntu 20.04

use 20.04 intead 22.04 and 24.04 because (in this date) it is compatible with mail server, openlitespeed.

# Requirements

- install docker sysbox: https://github.com/nestybox/sysbox

Sysbox is needed to nested docker containers.

## config

Rename `.env.example` to `.env` and change the variables

## run

```
make build
make mkdir
make fix_permissions
make up
make bt
14
```

## record changes to aapanel in the docker image

```
make commit
```

## stop

```
make rm
```
To "make up" twice, you need "make rm" first.

## Read this:

https://hub.docker.com/r/antonio24073/aapanel

https://github.com/antonio24073/aapanel-updater
