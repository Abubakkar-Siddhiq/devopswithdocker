# Use amazoncorretto base image
FROM amazoncorretto:8-alpine3.16

# App runs on port 8080
EXPOSE 8080

# Set the working directory
WORKDIR /usr/src/app

# Copy sources
COPY . .

# Build app
RUN ./mvnw package

# Set the entry point
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
