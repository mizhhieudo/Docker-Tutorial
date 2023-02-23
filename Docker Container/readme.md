## Docker Container

## What is container ?

![](https://docs.docker.com/engine/images/architecture.svg)

In docker, The container is a object contain that necessary to run application, include source code, library, and all dependency necessary. The container also included environment executed to run application independently compare to other environment

The each container was created by the images,This is a copy of system or application with other configs. When run the container,  Docker use image was created to create a environment executed independently with other container 

The use container help to the implement application be simple , because each container is a object independently and can move and implement on any host machine or environment installed Docker .

## How to management container in docker 

In Docker, the container is object dependency,can custom follow in many ways to fit with demand with application.The following is some option popular
to custom a container in Docker: 

1. `--name`:name of container 
2. `-d`: run container in daemon mode and don't link with terminal . 
3. `-it`: run container in interact mode and link with terminal. 
4. `-v`: link folder between container and host machine.
5. `-p` : link between with container and host machine
6. `--env`: customize for container.
7. `--network`: link container in individual network.
8. `--restart`: config container auto restart when stop 
9. `--user:`config user or group used container.
10. `--entrypoint`: customize command in container when container was ran

This is option to help custom options in container. 
Beside is some options popular in docker container:
1. `docker run`: create and run container from image

2. `docker start`: run the container was stop 

3. `docker stop`: stop the container running . 

4. `docker rm`:delete container was stopped

5. `docker ps`: list container running 

6. `docker logs`: view logs in a container 

7.  `docker inspect`: get information details of container 

8. `docker exec`: run command in a container running 

9. `docker restart`: restart a docker 

10. `docker commit`:create new a image from container running