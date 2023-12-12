# Use the base image with Java
FROM openjdk:17-jdk

# Set the working directory
WORKDIR /app
# Copy the packaged Spring Boot application JAR file into the container
COPY target/GestionCompetence-0.0.1-SNAPSHOT.jar back-end-gc.jar

# Expose the port the application runs on
EXPOSE 8888

# Define the command to run the application
CMD ["java", "-jar", "back-end-gc.jar"]