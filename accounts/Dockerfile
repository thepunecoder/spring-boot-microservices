# Use an official OpenJDK runtime as a parent image
FROM eclipse-temurin:17-jdk-jammy

#Information about the maintainer of the image
MAINTAINER thepunecoder.com

#Add the application's jar to the container
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts.jar

#Execute the jar file
ENTRYPOINT ["java", "-jar", "accounts.jar"]