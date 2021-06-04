# docker-compose-pull
Reference material for https://medium.com/@zhao.li/how-to-understand-pulling-images-with-docker-compose-236e323e541

Getting Started
---------------
1. install docker
1. install docker-compose
1. clone repository: `git clone --recursive https://github.com/zhao-lin-li/docker-compose-pull.git`
1. run `docker-compose pull` to pull the images

Verify Image
------------
```shell
$ docker image
REPOSITORY                TAG                 IMAGE ID            CREATED             SIZE
tomcat                    9.0.12              287b3865bc34        9 days ago          677MB
```
