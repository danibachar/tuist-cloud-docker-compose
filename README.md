# tuist-cloud-docker-compose
A simple Docker Compose file for on-premise testing of Tuist Cloud

# Run
1) Add the missing values for the relevant environment variables under the `tuist` service from [here](https://docs.tuist.io/cloud/on-premise#s3-compliant-storages)
2) You will need access to the tuist cloud docker file. (can be verified by running `docker pull ghcr.io/tuist/cloud-on-premise:latest`)
3) Run `docker compose up`
