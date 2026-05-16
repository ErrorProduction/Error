# Step 1: Use an official lightweight Java runtime image
FROM eclipse-temurin:17-jre-alpine

# Step 2: Set the working directory inside the container
WORKDIR /app

# Step 3: Copy your compiled JAR file into the container
# Replace "target/your-app.jar" with the actual path to your built JAR file
COPY target/your-app.jar app.jar

# Step 4: Expose the network port your Java app listens on (e.g., 8080 for Spring Boot)
EXPOSE 8080

# Step 5: Command to run your Java application
ENTRYPOINT ["java", "-jar", "app.jar"]
