FROM openjdk:8-jre-alpine
ADD service-configuration-0.0.1-SNAPSHOT.jar service-configuration.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/service-configuration.jar"]
