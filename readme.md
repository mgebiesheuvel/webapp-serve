# Laravel

## Serving app
1. Run `composer install` from the `src` directory to install all the required dependencies.
2. Run `docker-compose up -d` to serve the app and database; The app will be available on `http://127.0.0.1:8000`.

## Stopping app
1. Run `docker-compose down` to stop all the running containers;

## SSH into running container
1. Run `docker ps` to get the name of the container.
2. Run `docker exec -it <container name> /bin/bash` to access the container.
