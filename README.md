# Ubuntu + NodeJS base container for sitespeed.io

This is the base Docker container for sitespeed.io containing Ubuntu 20.04 and Node.js 16.x.

```
docker buildx build --push --platform linux/arm64,linux/amd64 -t sitespeedio/node:ubuntu-20.04-nodejs-16.13.2 . 

```
