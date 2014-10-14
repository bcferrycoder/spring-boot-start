Spring Boot Hello World
=======================

Spring Boot Hello World from http://spring.io/guides/gs/spring-boot/


## Run locally

  mvn package
  java -Dserver.port=1234 -jar target/gs-spring-boot-0.1.0.jar
  curl localhost:1234
  

## Push to Cloud Foundry

  cf push myapp -p target/gs-spring-boot-0.1.0.jar

