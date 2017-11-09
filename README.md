# Arachnys Docker Service

Aim of this image is to freeze the `arachnysdocker/athenapdf-service:2.10.0`.

## Build & Push

```
docker login
docker build -t ltgdocker/arachnys-docker-service:latest .
docker push ltgdocker/arachnys-docker-service:latest
docker tag ltgdocker/arachnys-docker-service:latest ltgdocker/arachnys-docker-service:$VERSION
docker push ltgdocker/arachnys-docker-service:$VERSION
```

## Current Version

Currently released `latest` version: `1.0.0`.
