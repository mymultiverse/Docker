# Docker
#### Docker Commands

Runing a container

    docker run -it "Container image"
Status of running containers

    docker ps
Stoping container with image name

    docker stop $(docker ps -q --filter ancestor = image)
    
#### References
[1.](https://stackoverflow.com/questions/32073971/stopping-docker-containers-by-image-name-ubuntu)

