# wait-for-healthy-container
Simple bash script to wait for a Docker container until the health check returns `healthy` or the timeout exceeded.

## Usage

Usage: `wait-for-healthy-container.sh <container name> [timeout]`

ie. `wait-for-healthy-container.sh my_app_container 120`

## Description

Script waits till the health check state of a container is 'healthy'. 

## Prerequisites

The docker container must have a **healthcheck** configured for this script to work.

### How to implement a docker container healthcheck

- [Implementing in a docker-compose file](https://docs.docker.com/compose/compose-file/compose-file-v3/#healthcheck)
- [Implementing in a Dockerfile](https://docs.docker.com/engine/reference/builder/#healthcheck)
- [Implementing via the docker run command](https://docs.docker.com/engine/reference/run/#healthcheck)
