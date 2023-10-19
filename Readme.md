# Silversurfer

Silversurfer is a JAVA 17/ Spring boot 2.7 backed micro service for working with insurance products offered by partners.

## Installation
Before running the service on your local machine. you will need to connect to dev/qa-2 database via ssh tunneling on localport and local port forwarding to 5432


```bash
mvn clean package spring-boot:run -Dspring-boot.run.profiles=local
```
