[![Build Status](https://github.com/kjkasi/python-image/actions/workflows/docker-image.yml/badge.svg)](https://github.com/kjkasi/python-image/actions/workflows/docker-image.yml)

# python-image-without-requirements
```
docker build -t python-image .
docker login
docker tag python-image:latest kjkasi/python-image-without-requirements:latest
docker push kjkasi/python-image-without-requirements:latest
docker save -o F:\python-image.tar kjkasi/python-image:latest
```
