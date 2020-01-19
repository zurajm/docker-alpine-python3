![Docker Build Status](https://img.shields.io/docker/build/zurajm/alpine-python3?style=flat-square)
![Docker Stars](https://img.shields.io/docker/stars/zurajm/alpine-python3?style=flat-square)
![Docker Pulls](https://img.shields.io/docker/pulls/zurajm/alpine-python3?style=flat-square)


Python 3.7 Docker image - Multiarch build
=========================================

Forked from [this repo](https://github.com/Docker-Hub-frolvlad/docker-alpine-python3), with automated multiarch build hooks from [this repo](https://github.com/cgiraldo/docker-hello-multiarch).

This image is based on Alpine Linux image, which is only a 5MB image, and contains
[Python 3.7](https://www.python.org/).

Download size of this image is only:

![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/zurajm/alpine-python3/latest?style=flat-square)


Usage Example
-------------

```bash
$ docker run --rm frolvlad/alpine-python3 python3 -c 'print("Hello World")'
```

Once you have run this command you will get printed 'Hello World' from Python!  Or use it interactivelly:

```bash
$ docker run -it --rm frolvlad/alpine-python3 python3
```


NOTE: `pip`/`pip3` is also available in this image.
