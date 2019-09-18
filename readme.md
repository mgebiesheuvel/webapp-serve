# Docker Compose configuration
A quick and easy way to serve web applications, both the app and MySQL database.

## Install a web applicaiton
1. Create a new directory `src` in the root folder of this project;
2. Add a web application (i.e. a Laravel app) in the newley created folder;

## Starting the containers
1. Run `docker-compose up -d` to serve the app and database; The app will be available on `http://127.0.0.1:8000`.

## Stopping the containers
1. Run `docker-compose down` to stop all the running containers;

## SSH into a running container
1. Run `docker ps` to get the name of the container.
2. Run `docker exec -it <container name> /bin/bash` to access the container.
