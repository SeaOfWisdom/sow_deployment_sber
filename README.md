# SeaOfWater.xyz Deployment Repository
This repository is dedicated to the deployment of SeaOfWater.xyz,
an application built with Docker containers and managed using Docker Compose. 
It provides a brief overview of the repository's purpose and how it is intended to function.

## Overview
SeaOfWater.xyz is a web application that consists of multiple services, 
including a web server, an Nginx reverse proxy, a JWT server, a library server,
MongoDB, and PostgreSQL. These services work together to provide a functioning application environment.

## Structure

Implies that the API and the frontend are located as the following:
    
    -sow_deployment
        -docker-compose.yaml
            ...
    -sow_frontend
        -certs
        -nginx.conf
            ...
    -sow_library
        ...

## Usage
```bash
docker-compose up -d --build
```
