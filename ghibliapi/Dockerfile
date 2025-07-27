# Start from an OpenJDK 17 image
FROM openjdk:17-jdk-slim

# Set a working directory
WORKDIR /app

# Copy the Maven build artifact (the JAR file)
COPY target/*.jar app.jar

# Expose port (default Spring Boot port)
EXPOSE 8080

# Run the JAR file
ENTRYPOINT ["java", "-jar", "app.jar"]
