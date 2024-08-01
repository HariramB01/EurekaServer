
FROM openjdk:17-jdk-alpine

COPY target/EurekaServer-0.0.1-SNAPSHOT.jar EurekaServer-0.0.1-SNAPSHOT.jar

# Expose the port that your application will run on
EXPOSE 8761

# Run the jar file
ENTRYPOINT ["java","-jar","/EurekaServer-0.0.1-SNAPSHOT.jar "]
