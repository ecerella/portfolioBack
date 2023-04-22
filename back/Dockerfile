
FROM amazoncorretto: 8-alpine-jdk
MAINTAINER eze
COPY target/eze-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]



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
