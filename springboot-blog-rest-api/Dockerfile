FROM eclipse-temurin:17

LABEL mentainer="java@gmail.com"

WORKDIR /app

COPY target/springboot-blog-rest-api-0.0.1-SNAPSHOT.jar /app/springboot-docker-demo.jar

ENTRYPOINT["java", "-jar", "springboot-docker.jar"]

