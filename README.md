# Angular CLI Docker Images
Dockerfiles for Angular CLI images.

## Docker Commands
```
docker pull akhilpb001/ng-cli:<version>
```
```
docker run -it --rm -p 4200:4200 -v "$PWD":/app akhilpb001/ng-cli:<version> sh
```

## Available Versions
- 11.2.8 (latest)

## Docker Repository
- https://hub.docker.com/repository/docker/akhilpb001/ng-cli