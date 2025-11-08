# Use OpenJDK 17
FROM eclipse-temurin:17-jdk-alpine

WORKDIR /app

# Copy the jar built by Maven
COPY target/*.jar app.jar

# Expose service port
EXPOSE 8300

# Run the Spring Boot jar
ENTRYPOINT ["java","-jar","app.jar"]
