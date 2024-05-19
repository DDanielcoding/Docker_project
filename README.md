# Dockerized Python Flask Web Application

## Introduction

This project demonstrates the process of dockerizing a simple Python Flask web application. The primary steps involved include creating the Flask application, writing a Dockerfile to containerize the application, and building and running the Docker container. Once set up, the Flask application can be accessed via a web browser at https://localhost:5000.


![architecture](https://github.com/DDanielcoding/Docker_project/assets/155651525/e8904606-fd2f-4596-93a6-c3571b9ceb46)


## Step 1: Create the Flask Application
Create a simple Flask application that serves a basic HTML page. The Flask app consists of an app.py file that defines the routes and logic for the application, as well as any templates or static files needed by the app.

## Step 2: Write the Dockerfile

Create a Dockerfile that defines the environment and dependencies needed to run the Flask application. The Dockerfile includes instructions for installing required libraries and frameworks, copying the Flask app files into the container, and setting the entrypoint for the container.

## Step 3: Build and Run the Docker container

<code>docker build -t myflaskapp .</code><br><br>

## Run the Docker container based on the image:
<code>docker run -p 5000:5000 myflaskapp</code><br><br>

## Accessing the Flask Application

Once the container is running, you can access the Flask application in your web browser at https://localhost:5000
