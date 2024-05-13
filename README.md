# lab3_Node
This is an example of deploying a Node.js Web Application using Docker on AWS EC2 with CI/CD.
The file app.js is the main application file for our Node.js web application.
The package.json file acts as the project descriptor for the Node.js application, listing metadata such as the app's name and version.
The Dockerfile is a script used by Docker to automate the building of container images, starting from a specified base image such as Node.js. It includes commands to copy the application files into the container, install necessary dependencies, and set the container to start the application upon launch. This file is crucial for packaging the application into a container.
