# Use Maven with JDK 11 as the base image
FROM maven:3.8.6-openjdk-11

# Set the working directory in the container
WORKDIR /app

# Copy the Maven configuration file and source code
COPY pom.xml .
COPY src ./src

# Run Maven to build the application, skipping tests to speed up the build process
RUN mvn package -DskipTests

# Expose the application port (update if your app uses a different port)
EXPOSE 8080

# Run the application
CMD ["java", "-jar", "target/project-0.0.1-SNAPSHOT.jar"]
