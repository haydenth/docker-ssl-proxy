# docker-ssl-proxy
Builds a basic nginx server that proxies incoming SSL calls to a target
docker.

### Build and Run the Proxy ###
Build the docker:

    sh build.sh [-d Target Docker (Default: bixel)]

Run the docker:

    sh build.sh [-p SSL Port (default: 443)] [-d Target Docker (Default:
    bixel)]