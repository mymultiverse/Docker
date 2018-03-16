# Docker
#### Docker Commands

Runing a container

    docker run -it "Container image"
Status of running containers

    docker ps
Stoping container with image name

    docker stop $(docker ps -q --filter ancestor = image)
