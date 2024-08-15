# Local Dev Docker Run 

This is work in progress to create a self-contained environment. This is first for local development but may
also include later work on a production arrangment using Docker and/or Kubernetes

## Running locally

## Build the container

cd to the docker-compose directory and run:

```
docker-compose build
```

### Set env variable

cd to the ehlc-curation directory and set the NANOBOT_DIR environment variable

```
 export NANOBOT_DIR=`pwd`
```

### Launch docker-compose

``` 
docker-compose up
```

### Navigate to nanobot

```
http://localhost:3000/table 
```