# Octopus CLI Docker image

This repository contains a Docker image for the new [_vNext_ Octopus CLI](https://github.com/OctopusDeploy/cli): `octopus`.

There are both `alpine` and `ubuntu 22.04` images built in this repository.

**Note: Please consider this repository provided as is.  If there are any issues please do not contact support.**

## Tags


The following images are built in this repo:

- alpine (tagged `latest` in [DockerHub](https://hub.docker.com/r/octopuslabs/octopus-cli/tags?page=1&name=latest))
- Ubuntu 22.04 

A new image will be built each time a new version of Octopus CLI is created.  

The tags are as follows:
- Latest
- [Version] For example `1.3.0`
- Latest-[architecture] For example `latest-alpine`
- [Version]-[architecture] For example `1.3.0-alpine`

The version tag corresponds to the version of the Octopus CLI installed on the image. 

You can retrieve a list of all available tags for octopuslabs/octopus-cli at in [DockerHub](https://hub.docker.com/v2/repositories/octopuslabs/octopus-cli/tags).

### Docker files

Tag | Dockerfile
---------| ---------------
alpine | [Dockerfile](https://github.com/OctopusDeployLabs/octopus-cli-docker/blob/main/alpine/dockerfile)
Ubuntu 22.04 | [Dockerfile](https://github.com/OctopusDeployLabs/octopus-cli-docker/blob/main/ubuntu-2204/dockerfile)
