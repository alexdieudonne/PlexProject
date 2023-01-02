

## Create a network (Do this command before launch the project otherwise docker will crash.)
- `docker network create -d bridge plex_school`

##URL Plex 
[http://127.0.0.1:32400/manage] 
localhost


## To run this project you have to use the following command
`docker-compose -f docker-compose_main.yml -f docker-compose.yml up -d`
<!-- - `docker-compose up -d` -->