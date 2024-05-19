# Docker_project
Basic docker project for showcase purposes

Dockerizing a single python flask web application.

Diagram illustrates the tree main steps involved with dockerizing a python flask web application

First step is to create a flask application. that serves as a basic HTML page the flask app consists of app.py file that defines the roads and logic for the application as well as any templates or static files needed by the app.

The 2nd step is to create a Docker file this step involves creating a docker file that defines the environment and dependencies needed to run the flask application.
The docker file includes instructions for installing any required libraries and Frameworks copying the flask app files into the container and setting the entrypoint for the container.

The 3rd step is to build and run the docker container. This steps involves building the docker image from the docker file and then running the container based on the image.

Once the container is running you can ask access to the flask application in your web browser at localhost:5000.

