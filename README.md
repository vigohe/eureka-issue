# Example for issue [#1142](https://github.com/spring-cloud/spring-cloud-netflix/issues/1142) spring-cloud-netflix

Eureka fails to load static resource when its running in a docker container. 

Docker image [https://hub.docker.com/r/vigohe/eureka/](https://hub.docker.com/r/vigohe/eureka/)

`docker run --rm --name eureka -p 8761:8761 vigohe/eureka`

To generate the image from the source just run:

`mvn clean package docker:build`
