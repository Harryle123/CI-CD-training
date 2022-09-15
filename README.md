# docker_flutter_basic

A new Flutter project.

## Getting Started


### Build image
docker build . -t flutter_docker 
### Run image container
docker run -i -p 8080:5000 -td flutter_docker

### Open local web
localhost:8080