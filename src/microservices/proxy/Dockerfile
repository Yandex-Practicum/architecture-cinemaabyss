FROM openjdk:21-slim

WORKDIR /app

COPY target/proxy-service-1.0.0.jar app.jar

EXPOSE 8000

ENTRYPOINT ["java", "-jar", "app.jar"]