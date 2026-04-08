# Use lightweight Java runtime
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy jar file (make sure you build it first)
COPY target/*.jar app.jar

# Expose Spring Boot port
EXPOSE 8080

# Run the app
ENTRYPOINT ["java", "-jar", "app.jar"]