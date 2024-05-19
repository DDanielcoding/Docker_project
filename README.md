# Dockerized Python Flask Web Application

## Introduction

This project demonstrates the process of dockerizing a simple Python Flask web application. The primary steps involved include creating the Flask application, writing a Dockerfile to containerize the application, and building and running the Docker container. Once set up, the Flask application can be accessed via a web browser at http://localhost:5000.


![architecture](https://github.com/DDanielcoding/Docker_project/assets/155651525/e8904606-fd2f-4596-93a6-c3571b9ceb46)


## Step 1: Create the Flask Application
Create a simple Flask application that serves a basic HTML page. The Flask app consists of an app.py file that defines the routes and logic for the application, as well as any templates or static files needed by the app.

## Step 2: Write the Dockerfile

Create a Dockerfile that defines the environment and dependencies needed to run the Flask application. The Dockerfile includes instructions for installing required libraries and frameworks, copying the Flask app files into the container, and setting the entrypoint for the container.

## Step 3: Build and Run the Docker container

<code>docker build -t myflaskapp .</code><br><br>


# Docker_project
Basic docker project for showcase purposes

Dockerizing a single python flask web application.

Diagram illustrates the tree main steps involved with dockerizing a python flask web application

First step is to create a flask application. that serves as a basic HTML page the flask app consists of app.py file that defines the roads and logic for the application as well as any templates or static files needed by the app.

The 2nd step is to create a Docker file this step involves creating a docker file that defines the environment and dependencies needed to run the flask application.
The docker file includes instructions for installing any required libraries and Frameworks copying the flask app files into the container and setting the entrypoint for the container.

The 3rd step is to build and run the docker container. This steps involves building the docker image from the docker file and then running the container based on the image.

Once the container is running you can ask access to the flask application in your web browser at localhost:5000.

