# Use the official OpenJDK image as a base
FROM tomcat:9-jdk11

# Copy the JAR file to the container
COPY build/libs/Backend-0.0.1-SNAPSHOT-plain.jar /usr/local/tomcat/webapps/

# Expose the port your app runs on
EXPOSE 8080

# Run the JAR file
ENTRYPOINT ["catalina.sh", "run"]
