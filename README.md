# Node_Nginx_Docker_Project

# Introduction:
Node.JS is a runtime environment, it is software that allows applications written in javascript to be executed on the underlying OS.

# Pre-configurations needed:

You will require Docker and Docker Compose to be installed in your system. 
To download follow the link:
For docker:- https://www.docker.com/products/docker-desktop 
For docker compose:- https://docs.docker.com/compose/install/

# Project Description:
In this project, I have used a docker-compose file to start two services Nginx server and node.js app.

# Docker compose file:
I have defined a basic text app in node.js and that I have passed as a command under services in the docker-compose file. 
Whatever command is defined under services that specify which command should run when the container gets started. After writing the docker-compose file I have used commands like docker-compose up command. as an output, this docker file will run the app first and then the Nginx server.

# Commands Used in the file:
``` $ docker-compose up -d ``` This command will pull all the defined images in the docker-compose file from the docker hub.
``` $ docker-compose down ``` This command will stop all the conatiners that are currently running due to our docker-compose file.
