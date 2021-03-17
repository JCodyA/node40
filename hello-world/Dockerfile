FROM java:8-jdk-alpine
COPY ./example/hello-world-0.0.1-SNAPSHOT.jar .
WORKDIR .
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "hello-world-0.0.1-SNAPSHOT.jar"]
