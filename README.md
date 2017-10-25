# docker-test

with gradle 
-----------
gradle build buildDocker 

with maven
----------
mvn install dockerfile:build

run docker image
----------------
docker run -p 8080:8080 -t springio/gs-rest-service
