# Docker Services
Services such as Databases in Docker Image. <br>
Used in Ubuntu 20.04.2 LTS

## PREREQUISITION:

<small>`NOT RECOMENDING INSTALLING USING APT-GET, version is not updated`</small>

- Docker Engine (Obviously) <br>
https://docs.docker.com/engine/install/ubuntu/

- Docker-compose<br>
https://docs.docker.com/compose/install/


## Contents:
- mongodb
- redis




## Guides:
- Removing Docker Element (Images, Container) <br>
 https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes

- {more} 

## Docker CheatSheet:
- Listing Docker Images:
    ```
    docker images
    ```
- Search for Docker Images in Hub
    ```
    docker search <search-phrase>
    ```

- Remove all dangling images, container, volumes, and network
    ```
    docker system prune
    ```

- List Docker Container
    ```
    docker ps
    ```
    - `-a` to list all running and stopped container

- Getting into Container Bash (terminal)
    ```
    sudo docker exec -it <container-name> bash
    ```
    - `-it` the `i` means <b>interactive</b>


<small>Roberto Johan Salim</small>