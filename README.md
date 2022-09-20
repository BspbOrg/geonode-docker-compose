# geonode-docker-compose

This repository contains a docker-compose configuration for a GeoNode instance.

## Requirements

- Docker
- Docker Compose

## Usage

### Setup

First need to create a `.env` file with the following content:

```bash
    # project name suffix for docker-compose
    COMPOSE_PROJECT_NAME=geonode3
    # environment to use
    SET_DOCKER_ENV=local
```    

Then run the following command to build the images:

```bash
    ./dc build
```

### Start

To start the GeoNode instance run the following command:

```bash
    ./dc up -d
```

### Stop

To stop the GeoNode instance run the following command:

```bash
    ./dc down
```

### Logs

To see the logs of the GeoNode instance run the following command:

```bash
    ./dc logs -f
```
