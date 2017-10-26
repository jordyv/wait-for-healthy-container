# wait-for-healthy-container
Simple bash script to wait for a Docker container till the health check returned 'healthy' or the timeout exceeded.

## Usage

Usage: `wait-for-healthy-container.sh <container name> [timeout]`

ie. `wait-for-healthy-container.sh my_app_container 120`

## Description

Script waits till the health check state of a container is 'healthy'. For implementing the Docker health check, please checkout [the Dockerfile reference](https://docs.docker.com/engine/reference/builder/#healthcheck) or [the Docker run reference](https://docs.docker.com/engine/reference/run/#healthcheck).
