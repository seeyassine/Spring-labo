FROM ubuntu:latest
LABEL authors="YASSINE"

# Use a lightweight OpenJDK base image
#FROM openjdk:17-jdk-slim

# Set the working directory
#WORKDIR /app

# Copy the Spring Boot JAR file into the container
#COPY target/*.jar app.jar

# Expose port 8080 (default port for Spring Boot)
#EXPOSE 8080

# Run the Spring Boot application
#CMD ["java", "-jar", "app.jar"]


#ENTRYPOINT ["top", "-b"]

FROM openjdk:17-oracle
VOLUME /tmp
COPY target/*.jar app.jar
ENTRYPOINT ["java","-jar", "app.jar"]