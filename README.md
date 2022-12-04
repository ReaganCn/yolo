# Yolo Ecommerce platform

## Author: Reagan Charana

## About the project

Yolo is a simple ecommerce platform written in reactjs and node. It uses the nosql database mongodb. 

## How to run
Utilizes separate containers for both frontend and backend. But are connected to the same network as defined on the `docker-compose.yml`

Make sure you have <a href="https://docs.docker.com/engine/install/"> Docker</a> and <a href="https://docs.docker.com/compose/install/"> Docker Compose</a> installed

Build using docker compose
 - Clone the project
 - Navigate into the project root directory: `cd yolo`
 - Run `docker-compose build` in your terminal to build the docker compose file.
 - Then run  `docker-compose up` to run the containers.

Finally Navigate to <a href="http://localhost:3000" target="_blank">localhost:3000</a> in your browser