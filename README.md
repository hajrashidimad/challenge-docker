# challenge-docker
![n-y-c](https://www.threatstack.com/wp-content/uploads/2017/06/docker-cloud-twitter-card.png)
## Description
This project aims to learn the basics of docker like create an image and run a container in command line.

## Installation
you can install docker from official page by clicking [here.](https://docs.docker.com/engine/install/ubuntu/)


## Build
To build your image, you can type in commande line:\

**$ docker build . -t app**
## Run
To run a container, you can type in your command line:

**$ docker run -t app**

## Folder hierarchy
app:\
    + - - - docker\
    &emsp;| Dockerfile\
    + - - - pipeline\
    &emsp;&emsp;+ - - - | model\
    &emsp;&emsp;&emsp;| model.py -> print a number between 1 and 400\
    &emsp;&emsp;+ - - - | preprocessing\
    &emsp;&emsp;&emsp;| preprocessing.py -> print a numpy array\
    &emsp;&emsp;+ - - - | utils\
    &emsp;&emsp;&emsp;| utils.py -> print "Hello World\"
## Libraries
we used numpy for creat an array, to install it.

**pip install numpy**

## Team
05.01.2021 by: HAJ RASHID imad


