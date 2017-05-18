# [Dockerfiles](https://github.com/mrorgues/dockerfiles)

This repository holds various Dockerfiles for images I create.
Some of them are GUI Apps.

## Requirements

Some of the dockerfiles may use the [ARG](https://docs.docker.com/engine/reference/builder/#arg) keyword.
Hence, docker 1.9+ is required.

## Build your own images

###### Run the following command lines:

```
$ git clone git@github.com:mrorgues/dotckerfiles.git && cd dockerfiles/<PROJECT>
$ docker login
$ docker build --no-cache -f Dockerfile -t <DOCKER_HUB_REPO>/<PROJECT> .
$ docker push <DOCKER_HUB_REPO>/<PROJECT>
```

## More information
Please find more information here: http://wiki.ros.org/docker/Tutorials/GUI
