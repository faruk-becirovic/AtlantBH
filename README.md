# AtlantBH
This repository contains files necessary for running basic microservices application available on [GitHub](https://github.com/kkenan/basic-microservices) in 3 Docker containers. The _compose.yml_ file is used to build three Docker images:
1. spring; for spring-boot aplication available in the previously mentioned GitHub repository,
2. node; for node application, also available in the GitHub repository,
3. postgres; from official postgres image available on [DockerHub](https://hub.docker.com/_/postgres)

## Prerequisites
* Installed instance of docker on your machine 
* Access to the root user or user with root privilages

## Starting
To start _basic-microservices_ on your local machine clone this repository and run the following command from within the root of this directory:

  `docker compose up`
