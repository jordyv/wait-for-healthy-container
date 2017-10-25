# wait-for-healthy-container
Simple bash script to wait for a Docker container till the health check returned 'healthy' or the timeout exceeded.

## Usage

Usage: wait-for-healthy-container.sh <container name> [timeout]

ie. `wait-for-healthy-container.sh my_app_container 120`
