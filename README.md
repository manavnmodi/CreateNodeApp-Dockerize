# Dockerize-CreteNodeApp
Node Application Without AlpineOS

## Installation

Download [Docker Desktop](https://www.docker.com/products/docker-desktop/) or if already installed pull from [Dockerhub](https://hub.docker.com/r/manav23/node).

```bash
#Image pull from Dockerhub
Docker pull manav23/nodewithalpine

#See docker image is pulled ?
Docker images

#start container on your hostmachine with this localhost port number
Docker container run -p 8000:8000 manav23/node
```
