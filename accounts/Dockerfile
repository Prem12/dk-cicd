# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM openjdk:17-jdk-slim

# Simply the artifact path
ARG artifact=target/accounts-0.0.1-SNAPSHOT.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
