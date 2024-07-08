# Octopus CLI Docker image

This repository contains Dockerfiles used to build container images for the [Octopus CLI](https://github.com/OctopusDeploy/cli) called: `octopus`.

## Platforms

Images are typically available for:

- `linux/amd64` (based on `alpine`)

## Available images

The following images are built from this repository:

- [octopus-cli](#octopus-cli) (`octopuslabs/octopus-cli`)
- [octopus-cli-ci](#octopus-cli-ci) (`octopuslabs/octopus-cli-ci`)
- [octo-ci](#octo-ci) (`octopuslabs/octo-ci`)

### Octopus CLI

This image contains the `octopus` [command line tool](https://github.com/OctopusDeploy/cli/blob/main/README.md) (written in Golang).

A new image is built each time a new version of the `octopus` CLI is detected. The version tag corresponds to the version of the `octopus` CLI installed on the image.

#### Tags

- `octopuslabs/octopus-cli:latest`
- `octopuslabs/octopus-cli:latest-alpine`
- `octopuslabs/octopus-cli:VERSION`
- `octopuslabs/octopus-cli:VERSION-alpine`

You can retrieve a list of all available tags on [DockerHub](https://hub.docker.com/r/octopuslabs/octopus-cli/tags).

##### Deprecated tags

Octopus CLI images that are tagged with Ubuntu derivatives are no longer maintained. For example:

- `octopuslabs/octopus-cli:latest-ubuntu.2004`
- `octopuslabs/octopus-cli:latest-ubuntu.2204`

## Support

If you find a bug or encounter a problem with these images, please raise an [issue](https://github.com/OctopusDeployLabs/workertools/issues).
