# Use a base JDK image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy built jar file into the container
COPY target/*.jar app.jar

# Expose the port your app runs on (update if different)
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]
