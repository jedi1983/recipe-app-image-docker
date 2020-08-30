# recipe-app-image-docker
this is to test deployment using docker image

this repo is only consisting 1 docker-compose.yml, this will download application that is created using Django Python as an image from Docker image,
so we could use this application on any development machine, what could this be extend for?, well you could create this kind of method to deploy to server without 
having the Code directly on the server by only using build image push to docker repo and pull the repo and run it on the server.

ps : if you are using DB on different server you will not need to put DB services in compose file, but be sure to put credential on an .env file and build
directly on the image.
