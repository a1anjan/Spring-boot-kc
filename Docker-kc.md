## Create a docker file for your application docker image.

FROM java:8
WORKDIR /
COPY HelloWorld.jar HelloWorld.jar
EXPOSE 8080
CMD java - jar HelloWorld.jar


## Comand to build docker image: 

docker build . -t <image-name>:<tag-name>

link: https://docs.docker.com/engine/reference/commandline/build/



Imp links: 

https://dzone.com/articles/spring-boot-development-with-docker

https://hellokoding.com/full-stack-crud-web-app-and-restful-apis-web-services-example-with-spring-boot-jpa-hibernate-mysql-vuejs-and-docker/

https://github.com/hellokoding/hellokoding-courses/tree/master/springboot-examples/springboot-crud-mysql-vuejs

https://github.com/ahstn/docker-spring-react

https://hellokoding.com/restful-api-example-with-spring-boot-spring-data-rest-and-mysql/


