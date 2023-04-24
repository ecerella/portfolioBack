FROM amazoncorretto:11-alpine-jdk
MAINTAINER eze
COPY target/eze-0.0.1-SNAPSHOT.jar eze-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/eze-0.0.1-SNAPSHOT.jar"]



#FROM openjdk:17-alpine AS builder

#COPY ../.mvn .mvn
#COPY ../mvnw .
#COPY ../pom.xml .
#COPY ../src src
#RUN chmod +x mvnw

#RUN ./mvnw clean package

#FROM openjdk:17-alpine

#COPY --from=builder target/*.jar /app.jar

#EXPOSE 8080

#ENTRYPOINT ["java","-jar","/app.jar"]
