# Docker
#### Docker Commands

Runing a container

    docker run -it "Container image"
    
start the container
     
    sudo docker start container_name

open a new bash shell in this container
    
    sudo docker exec -it container_name bash

Status of running containers

    docker ps
Stoping container with image_name

    docker stop $(docker ps -q --filter ancestor = image)
    
Remove container

    sudo docker rm container_name
    
#### References
[1.](https://stackoverflow.com/questions/32073971/stopping-docker-containers-by-image-name-ubuntu)

