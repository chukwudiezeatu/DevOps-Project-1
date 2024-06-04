In this project, we are going to build a simple CI/CD pipeline from scratch using tools like Flask, Docker, Git, Github, Jenkins and Kubernetes.

Prerequisites
Python
Flask
Docker
Git and Github
Jenkins
Kubernetes
Linux machine
Steps in the CI/CD pipeline
Create a "Hello world" Flask application
Write basic test cases
Dockerise the application
Test the code locally by building docker image and running it
Create a github repository and push code to it
Start a Jenkins server on a host
Write a Jenkins pipeline to build, test and push the docker image to Dockerhub.
Set up Kubernetes on a host using Minikube
Create a Kubernetes deployment and service for the application.
Use Jenkins to deploy the application on Kubernetes
Project structure
app.py - Flask application which will print "Hello world" when you run it
test.py - Test cases for the application
requirements.txt - Contains dependencies for the project
Dockerfile - Contains commands to build and run the docker image
Jenkinsfile - Contains the pipeline script which will help in building, testing and deploying the application
deployment.yaml - Kubernetes deployment file for the application
service.yaml - Kubernetes service file for the application
