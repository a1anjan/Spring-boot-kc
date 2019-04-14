## Create a docker file for your application docker image.

FROM java:8

WORKDIR /

COPY HelloWorld.jar HelloWorld.jar

EXPOSE 8080

CMD java - jar HelloWorld.jar


## Comand to build docker image: 

docker build . -t <image-name>:<tag-name>

link: https://docs.docker.com/engine/reference/commandline/build/

## Docker link to another conatiner 

docker run -d --name sqlplus --link db:db -p 1521:1521 sqlplus

docker run -e POSTGRES_USER=docker -e POSTGRES_PASSWORD=docker -e POSTGRES_DB=docker library/postgres

$ docker exec -it my-postgres bash



Imp links: 

https://dzone.com/articles/spring-boot-development-with-docker

https://hellokoding.com/full-stack-crud-web-app-and-restful-apis-web-services-example-with-spring-boot-jpa-hibernate-mysql-vuejs-and-docker/

https://github.com/hellokoding/hellokoding-courses/tree/master/springboot-examples/springboot-crud-mysql-vuejs

https://github.com/ahstn/docker-spring-react

https://hellokoding.com/restful-api-example-with-spring-boot-spring-data-rest-and-mysql/

https://stackoverflow.com/questions/19897743/exposing-a-port-on-a-live-docker-container

rr->  https://medium.com/@rrfd/setting-up-docker-postgresql-connecting-locally-using-advanced-functions-d8fe3bd58de6






