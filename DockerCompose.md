
# Docker Compose 

Docker compose is a simple yet powerful tool that is used to defining and run multiple containers as a single service.
For example, suppose you have an application which requires Nginx as a web server and PostgreSQL as a database service. In this case by docker-compose, you can create one single file (docker-compose.yml ) which will create both the containers as a single service without starting each separately

## How to install docker compose on Ubuntu
If you are using windows or Mac machine then docker compose is already install 

Step 1. Run Below command on your terminal 
```sh
sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```
Step 2: Apply executable permissions to the binary
```sh
sudo chmod +x /usr/local/bin/docker-compose
```
Step 2: Check the Version of docker Compose
```sh
docker-compose -v 
or 
docker-compose --version 
or 
docker-compose version 
```