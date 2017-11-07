# How to install and use Docker?

## INSTALL DOCKER

#### Under construction

...

#### Check the installation

$ docker run hello-world

#### Docker subcommand

$ docker

#### Help subcommand

~ docker _docker subcommand_ --help


## DOCKER IMAGES

#### Looking for images in Docker Hub

$ docker search _image_

#### Download docker's image

$ docker pull _image_

#### List the images downloaded

$ docker images

#### Remove an image

$ docker rm _image_


## DOCKER CONTAINER

#### Execute docker container

$ docker run -it _image_
  
  - t: launch console

#### Status of containers in execution

$ docker ps

#### Stop a container

$ docker stop _image or containerID_

#### Restart a container

$ docker restart _image or containerID_

#### Remove the image of a container in execution

$ docker rm --force _image or containerID_


## INSIDE CONTAINER

#### Leave the container

$ exit


## REFERENCES

https://github.com/manuparra/MasterDegreeCC_Practice/blob/master/starting_docker.md <br>
https://www.digitalocean.com/community/tutorials/como-instalar-y-usar-docker-en-ubuntu-16-04-es <br>
