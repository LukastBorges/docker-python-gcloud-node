# Python with Node env to run tests

Base image with:
- python 2.7.12
- node v6.11.2
- npm v3.10.10
- yarn 0.27.5
- chromedriver 2.31
- phantomjs 2.1.1

# Docker hub

[lukasborges/python-gcloud-node](https://hub.docker.com/r/lukasborges/python-gcloud-node/)

# Commands


## Build the image
```
docker build -t lukastborges/python-gcloud-node:v6 .
```

## Push the image

```
docker push lukastborges/python-gcloud-node
```
