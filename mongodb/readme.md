# MONGOD Docker Composer

## FIRST TIME SETUP:
- Make a directory named `database`
  ```
  mkdir database
  ```

## HOW TO RUN:
- CD to where `docker-compose.yml` is
- enter command `sudo docker-compose up -d` <br>
  <small>`-d` used to run process in the background</small>

## HOW TO USE:
-   ## Access Container Terminal:
    Get inside container bash (terminal)
    ```
    sudo docker exec -it mongodb bash
    ```
    open mongo cli by typing 
    ```
    mongo
    ```
-   ##

References:
- MongoDB on docker <br>
  https://www.bmc.com/blogs/mongodb-docker-container/

- Docker Compose Installation<br>
  https://docs.docker.com/compose/install/
