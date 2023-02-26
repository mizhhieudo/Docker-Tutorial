# Docker Volume

![](https://devopedia.org/images/article/101/8323.1565281088.png)
 
 ## What is Docker volume 

 Docker volume is a mechanism stored and management data in the container docker. It allows saved data outside container,help for the management data easy and minimize lost data when container deleted or modified 

The docker volume is a folder or file managed by Docker pm system host or network disk and can linked with one or multiple other container.The volume created by command `docker volume create`, and can be linked with a container across option `-v`.

When docker created by a volume, Docker will create empty folder in container and link to volume. Any data stored in this folder in container will store om volume, it will lost when container deleted or stop . 

The volume docker can used to stored like database,files configs,portable file,log file and more...
