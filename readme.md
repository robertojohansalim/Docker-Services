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
- postgresql

## How to Use this Repo:
- `cd` to service directory
- follow instruction there for first time setup <small>(usually making directory)</small>
- to start run command:
    ```
    docker-compose up -d
    ```
    - `-d` to run command in the background and free the terminal
- confirm running service using 
    ```
    docker ps
    ```
- to stop service, cd over to service directory and run:
    ```
    docker-compose stop
    ```


## Dokcer Guides:
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