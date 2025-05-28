FROM openjdk:21-slim

WORKDIR /app

COPY target/events-service-1.0.0-jar-with-dependencies.jar app.jar

EXPOSE 8082

ENTRYPOINT ["java", "-jar", "app.jar"]
