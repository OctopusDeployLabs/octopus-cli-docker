# Octopus CLI Docker image

This repository contains Dockerfiles used to build container images for the [Octopus CLI](https://github.com/OctopusDeploy/cli) called: `octopus`.

## Platforms

Images are typically available for:

- `linux/amd64`
- `linux/arm64`

 These are based on the `alpine` Linux distro.

## Available images

The following DockerHub images are built from this repository:

- [octopus-cli](#octopus-cli) (`octopuslabs/octopus-cli`)
- [octopus-cli-ci](#octopus-cli-ci) (`octopuslabs/octopus-cli-ci`)

We also publish the same images to GitHub's Container Registry (GHRC) too:

- `ghcr.io/octopusdeploylabs/octopus-cli`
- `ghcr.io/octopusdeploylabs/octopus-cli-ci`

### Octopus CLI

This image contains the `octopus` [command line tool](https://github.com/OctopusDeploy/cli/blob/main/README.md) (written in Golang).

A new image is built each time a new version of the `octopus` CLI is detected. The version tag corresponds to the version of the `octopus` CLI installed on the image.

#### Tags

- `octopuslabs/octopus-cli:latest`
- `octopuslabs/octopus-cli:VERSION`

You can retrieve a list of all available tags on [DockerHub](https://hub.docker.com/r/octopuslabs/octopus-cli/tags).

##### Deprecated tags

Octopus CLI images that are tagged with Ubuntu derivatives are no longer maintained. For example:

- `octopuslabs/octopus-cli:latest-ubuntu.2004`
- `octopuslabs/octopus-cli:latest-ubuntu.2204`

### Octopus CLI CI

This is a CI-server compatible image containing the `octopus` [command line tool](https://github.com/OctopusDeploy/cli/blob/main/README.md).
It's identical to the [octopuslabs/octopus-cli](https://hub.docker.com/r/octopuslabs/octopus-cli) image except that its `ENTRYPOINT` method is overriden to be empty (`""`).

A new image is built each time a new version of the `octopus` CLI is detected. The version tag corresponds to the version of the `octopus` CLI installed on the image.

#### Tags

- `octopuslabs/octopus-cli-ci:latest`
- `octopuslabs/octopus-cli-ci:VERSION`

You can retrieve a list of all available tags on [DockerHub](https://hub.docker.com/r/octopuslabs/octopus-cli-ci/tags).

## Support

If you find a bug or encounter a problem with these images, please raise an [issue](https://github.com/OctopusDeployLabs/octopus-cli-docker/issues).
