# syntax=docker/dockerfile:1
  
FROM openjdk:11.0.2-jre-slim

EXPOSE 8080

WORKDIR /app

COPY ./order-service-0.0.1-SNAPSHOT.jar ./

CMD ["java","-jar","./order-service-0.0.1-SNAPSHOT.jar"]

