[![tests](https://github.com/ddev/ddev-addon-template/actions/workflows/tests.yml/badge.svg)](https://github.com/ddev/ddev-addon-template/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

# ddev-addon-template <!-- omit in toc -->

- [What is ClamAV?](#what-is-clamav)
- [TODO](#todo)
- [Getting started](#getting-started)

## What is ClamAV?

ClamAv is <>
<https://hub.docker.com/r/clamav/clamav/>
<https://docs.clamav.net/manual/Installing/Docker.html>

**Work In Progress**

This project is currently NOT functioning. Hopefully, the maintainer / community can get things moving.

## TODO

- [X] Mount project to `/scandir`
- [ ] Add DDEV command to scan directory/s
- [ ] Add pathway to update virus defs.
- [ ] Add meaningful tests

## Getting started

1. Install the `ddev-clamav` addon and restart DDEV.

   ```shell
   ddev get tyler36/ddev-clamav
   ```

**Contributed and maintained by [@CONTRIBUTOR](https://github.com/CONTRIBUTOR) based on the original [ddev-contrib recipe](https://github.com/ddev/ddev-contrib/tree/master/docker-compose-services/RECIPE) by [@CONTRIBUTOR](https://github.com/CONTRIBUTOR)**

**Originally Contributed by [somebody](https://github.com/somebody) in <https://github.com/ddev/ddev-contrib/>
