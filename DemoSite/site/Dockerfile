FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY ./site /app
WORKDIR /app
RUN ./mvnw clean package
ENTRYPOINT ["java", "-jar", "target/demo-site-1.0.0-SNAPSHOT.jar"]