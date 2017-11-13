# docker-a0deploy

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to deploy tenant configuration to [auth0](https://auth0.com). 

## Details

### Base Image

* [node (boron)](https://hub.docker.com/r/library/node/) - The latest Node LTS (Boron) image

### Additional Node Modules

* [Auth0 Deploy CLI](https://github.com/auth0/auth0-deploy-cli) - Auth0 Deploy CLI.

## Colophon

Inspired by [docker-firebase](https://github.com/devillexio/docker-firebase).