# Rails Deployment Compose File

by Sunil Prajapati

### Running the containers
Make a new docker network if necessary

`docker network create <network_name>`

Please run the command below to start the containers

`docker compose up -d`

To stop the containers, run the command

`docker compose down --remove-orphans`