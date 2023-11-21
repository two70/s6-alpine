# Originally forked from oznu/docker-s6-alpine

Since the main repo is no longer maintained, I forked it to keep it up to date because it's used as the base image for docker-cloudflare-ddns image.

# s6-alpine

This is a base Apline image with the [S6 Overlay](https://github.com/just-containers/s6-overlay)

[Alpine Linux](https://alpinelinux.org/) + [S6 Overlay](https://github.com/just-containers/s6-overlay)

## Usage

See the [S6 Overlay Documentation](https://github.com/just-containers/s6-overlay) for details on how to manage services.

Version relates to Alpine version

x86_64:

```shell
docker run ghcr.io/two70/s6-alpine
```
or 
```shell
docker run ghcr.io/two70/s6-alpine:3.18.1
```

ARM:

```shell
docker run ghcr.io/two70/s6-alpine
```
or 
```shell
docker run ghcr.io/two70/s6-alpine:3.18.1
