# Docker overview 
![](https://s3-ap-southeast-1.amazonaws.com/homepage-media/wp-content/uploads/2021/01/28133406/docker-banner.png)

## What is Docker ?

**Docker** is a platform allows users to package and run applications in an isolated environment called is `container`. These Containers maybe run on any system with installed Docker 

## What is difference between Docker and platform virtual ? 

![](https://i0.wp.com/techieswiki.com/wp-content/uploads/2020/12/Docker-and-Virtual-Machine-architecture.jpg?fit=1284%2C642&ssl=1)

The image above describes the architecture's docker vs virtual machine.
- Virtual machine packing include [OS system,bins/libs,app] .So if users use many virtual machine will costly resources.
- Docker packing include [bins/libs,app].The docker use resources common with OS Physics machine .

## The docker's architecture

![](https://devopedia.org/images/article/101/8323.1565281088.png)

The docker's architecture include: 

1. Docker Engine : This is the core ingredient of docker, have to mission management and run the container. It includes daemon (dockerd) to management container,the REST API to allow the applications  interact with the dockers and the command line interface (CLI) allows to allows user interaction with Docker 

2. Docker image: This's the package command and environment necessary to run an application on the docker. It include all ingredient necessary of application,include the libraries,the configs file and how to implement them. Each the container. The images was created by write `Dockerfile` or download from `Docker Hub`

3. Docker Container:This's a version run by docker images.It provides the environment isolated to run the application. Each container will have the system resource (cpu,memory,disk) isolated and maybe will share with other container  

4. Docker registry: This's stores the images of Docker. Docker Hub is a community Docker Registry, where everyone can search,download the images already packed .The Users can initial create a docker registry individually to manage my images.

5. Docker compose: This is tool allows the user define and run the applications multiple container .It allows user define the containers,configs network and service then run all the container in command easy 
