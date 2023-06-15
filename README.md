# Octopus CLI Docker image

This repository contains a Docker image for the new [_vNext_ Octopus CLI](https://github.com/OctopusDeploy/cli): `octopus`.

The image is built from the `alpine` platform.

**Note: Please consider this repository provided as is.  If there are any issues please do not contact support.**

## Tags

The version tag corresponds to the version of the Octopus CLI installed on the image. 
A new image will be built each time a new version of Octopus CLI is created.  

The tags are as follows:
- Latest
- [Version] For example `1.3.0`
- Latest-[architecture] For example `latest-alpine`
- [Version]-[architecture] For example `1.3.0-alpine`

### octopus-cli Tags

Tag | Dockerfile
---------| ---------------
alpine| [Dockerfile](https://github.com/OctopusDeployLabs/octopus-cli-docker/blob/main/alpine/dockerfile)

You can retrieve a list of all available tags for octopuslabs/octopus-cli at https://hub.docker.com/v2/repositories/octopuslabs/octopus-cli/tags.
