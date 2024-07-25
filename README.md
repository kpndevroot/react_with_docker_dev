# React with docker environment

## Requirement

1.Docker
2.docker-compose

## setup up

### build the docker images

```bash
docker-compose build
```

## run the server

```bash
docker-compose up -d
```

## run the build and server

```bash
docker-compose build && docker-compose up -d
```

## access the logs

### for the web logs

```bash
docker-compose logs -f web
```

### for the test logs

```bash
docker-compose logs -f test
```
