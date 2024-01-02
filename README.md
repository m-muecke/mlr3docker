# mlr3docker
<!-- badges: start -->

[![license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://opensource.org/licenses/GPL-3.0)

<!-- badges: end -->

## Overview

Docker Images for [mlr3](https://github.com/mlr-org/mlr3) on [Dockerhub](https://hub.docker.com/u/mlrorgdocker) for a [slim installation](https://hub.docker.com/r/mlrorgdocker/mlr3-slim) and a [full installation](https://hub.docker.com/r/mlrorgdocker/mlr3-full).

You can trigger the build and push to dockerhub manually for [the slim image](https://github.com/mlr-org/mlr3docker/actions/workflows/mlr3slim.yml) and [the full image](https://github.com/mlr-org/mlr3docker/actions/workflows/mlr3full.yml).

## Images

The images build on `rocker/r-ver:latest`. See [rocker-versioned2](https://github.com/rocker-org/rocker-versioned2) repo for details.

| image                                                        | description    | metrics                                                                                                                |
| ------------------------------------------------------------ | -------------- | ---------------------------------------------------------------------------------------------------------------------- |
| [mlr3-slim](https://hub.docker.com/r/mlrorgdocker/mlr3-slim) | Adds mlr3verse | [![](https://img.shields.io/docker/pulls/mlrorgdocker/mlr3-slim.svg)](https://hub.docker.com/r/mlrorgdocker/mlr3-slim) |
| [mlr3-full](https://hub.docker.com/r/mlrorgdocker/mlr3-full) | Adds mlr3verse & mlr3extralearners incl. dependencies | [![](https://img.shields.io/docker/pulls/mlrorgdocker/mlr3-full.svg)](https://hub.docker.com/r/mlrorgdocker/mlr3-slim) |
