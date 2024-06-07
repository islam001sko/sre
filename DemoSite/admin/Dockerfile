FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY ./ /app
WORKDIR /app
RUN ./mvnw clean package
ENTRYPOINT ["java", "-jar", "target/demo-admin-1.0.0-SNAPSHOT.jar"]
