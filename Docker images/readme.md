# Image in Docker


## Define

Docker images is the copy file but read only of the systems and the folders packed in format specifically. It contains all ingredients necessary to initialize run a application, include libraries and source code, configure

The docker image have created by a docker Dockerfile. It's document contain a set of instructions to build a image . Dockerfile includes directives to copy the files,configure software and configure application

When the docker image is created, it saved in a image repository,so that later used to create the container (instances) Docker. The each docker image has a unique name, defined follow format `name`: `version`.Example image of ubuntu can be named is ubuntu:latest

When your create a container from the docker image, Docker will create the copy of that image and run application in container latest . All changes executed in container don't affect to the original image, therefore it can use to create the others container wither others version of application

## Command management docker

Belows is some command popular to management Docker image:

![](https://docs.docker.com/engine/images/architecture.svg)

1. Docker build : This command used to build a image from Dockerfile
2. Docker images :This command list all images now available now available in Docker host
3. Docker pull : This command used to download
   a image form image repository
4. Docker push: This command used to push a image to image repository
5. Docker rmi: This command used to delete or multiple images from Docker host

6. Docker tag: this command used to rename or tag the image

7. Docker history : This command used to display the history was changed on a image

8. Docker inspect: This command display information details about image.

9. Docker save: This command used to saved a image become a file `tar` format

10. Docker load: This command used loaded image from file format `tar` type
