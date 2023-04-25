FROM amazoncorretto:8-alpine-jdk
MAINTAINER eze
EXPOSE 8080
COPY "./target/eze-0.0.1-SNAPSHOT.jar" "ezeApp.jar"
ENTRYPOINT ["java","-jar","/ezeApp.jar"]



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
