FROM openjdk:8
RUN mkdir /app
WORKDIR /app
COPY target/docker-demo-0.0.1-SNAPSHOT.jar /app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "docker-demo-0.0.1-SNAPSHOT.jar"]