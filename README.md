HELLO DOCKER!
A simple docker image using JavaScript


Steps to build and publish the image on docker hub.

1. Clone this repo

2. Under the root folder, open a terminal and type

        docker build -t <image-name> .

        docker login

        docker push <hub-user>/<repo-name>:<tag>

This repository has a workflow to automatic build and publish the image at releases.

1. On repository page: settings -> secrets

        Create a secret DOCKER_USERNAME and put your dockerhub username
        Create a secret DOCKER_TOKEN and put your dockerhub token
        
2. Create a new release

    