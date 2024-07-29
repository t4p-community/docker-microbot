# Microbot Container

## Purpose

Docker image running:

- [Alpine Linux](https://github.com/gliderlabs/docker-alpine)
- [Nginx](http://nginx.org/)
- Microbot image/unique html content

This container is for demonstrating docker orchestration.

- Docker
- Mesos
- Marathon
- Kubernetes

## Usage

```sh
docker run -d -p "8080:80" t4p-community/microbot
```


Special thanks to [Patrick O'Connor](https://github.com/dontrebootme/docker-microbot) for the original microbot.