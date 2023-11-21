# FINAL PROJECT - DOCKER COURSE
## DESCRIPTION
This is the final project for the Docker course. Random ipsum text. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis egestas rhoncus. Donec facilisis fermentum sem, ac viverra ante luctus vel. Donec vel mauris quam. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla convallis egestas rhoncus. Donec facilisis fermentum sem, ac viverra ante luctus vel. Donec vel mauris quam.
### CONTRIBUTORS
- [Lucas RATIARAY](https://lucasratiaray.fr)
- [Thibault PERROUAS](https://thibaultperrouas.fr)
## INSTALLATION
### REQUIREMENTS
- Docker
- Docker-compose
### PROCEDURE
1. Clone the repository
2. Run `docker-compose up -d`
3. Go to [localhost:8081](http://localhost:8081) for the first server.
4. Go to [localhost:8082](http://localhost:8082) for the second server.
5. Enjoy !
## USAGE
### COMMANDS
- `docker-compose up -d` : Start the containers in background
- `docker-compose down` : Stop the containers
- `docker-compose logs -f` : Show the logs of the containers
### URLS
- [localhost:8081](http://localhost:8081) : First server
- [localhost:8082](http://localhost:8082) : Second server
## DOCUMENTATION
### ARCHITECTURE
- php
    - Dockerfile
- server
    - nginx1
        - default.conf
    - nginx2
        - default.conf
- www
    - HERE ARE THE FILES OF THE APPLICATION
- docker-compose.yml
- README.md
### IMAGES
- php:8.2-fpm-alpine
- nginx:lastest
### PORTS
- 8081:80
- 8082:80
### VOLUMES
- ./www:/var/www/html
### NETWORKS
- default
## ROADMAP
- [x] Create the repository
- [x] Create the Dockerfile
- [x] Create the docker-compose.yml
- [x] Create the server configuration
- [x] Clone the application
- [x] Create the README.md
