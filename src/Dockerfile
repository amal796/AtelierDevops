# Use the openjdk11 image from Docker Hub
FROM openjdk:11

# Expose the port of your Spring Boot application
EXPOSE 8080

# Copy the jar of the application into the container
ADD target/timesheet-devops-1.0.jar /timesheet-devops-1.0.jar

# Command to run the Spring Boot application
ENTRYPOINT ["java", "-jar", "/timesheet-devops-1.0.jar"]
