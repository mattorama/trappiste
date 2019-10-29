# trappiste

python machine learning deployment

## Purpose

Deploy Python data products.

## Prerequisites

Docker. VSCode for Python remote debugging.

## Getting started

* export the environment variables

```
source export_env.sh
```

* build the containers and launch the services

```
make build
make up
```

* run any of the commands in the `Makefile`, e.g.,

```
make pyapp
```
