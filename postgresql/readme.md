# POSTGRESQL Docker Composer

## FIRST TIME SETUP:
- Make a directory named `data`
  ```
  mkdir data
  ```
## HOW TO RUN:
- CD to where `docker-compose.yml` is
- enter command `sudo docker-compose up -d` <br>
  <small>`-d` used to run process in the background</small>

## Access Docker From PSQL
``` 
psql -h localhost -p 5432 -U postgres
```
- `-U` as user postgres
- will ask for password (default : `postgres`)