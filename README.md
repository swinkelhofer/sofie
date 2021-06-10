# SoFiE - The Socat Fileserver Experiments

[![Release](https://github.com/swinkelhofer/sofie/actions/workflows/release.yml/badge.svg)](https://github.com/swinkelhofer/sofie/actions/workflows/release.yml)

A minimal fileserver based on the swiss-army-knife-tool Socat - completely written in Bash.
The goal of SoFiE was to minimize dependencies to only a subset that (almost) any Linux distro is shipping.

Et voilà, without further need to explain, here we go:

```
NAME:
    SoFiE -- The Socat Fileserver Experiments
USAGE:
    ./sofie [options]
OPTIIONS:
    -p|--listen-port                    Port to listen on
    -b|--base-directory                 Base directory to serve from
    -d|--disable-directory-listing      Disable listing content of directories
    -h|--help                           Print this help
```
