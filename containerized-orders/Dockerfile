FROM openjdk:11-jdk-slim
MAINTAINER Taner Diler <taner.diler@gmail.com>
ADD target/containerized-orders-1.0.0-SNAPSHOT.jar containerized-orders.jar
ENTRYPOINT ["java", "-jar", "/containerized-orders.jar"]
EXPOSE 2222
