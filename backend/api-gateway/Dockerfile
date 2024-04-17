FROM openjdk:17-alpine
WORKDIR /api-gateway
COPY target/*.jar /api-gateway/app.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "/api-gateway/app.jar"]