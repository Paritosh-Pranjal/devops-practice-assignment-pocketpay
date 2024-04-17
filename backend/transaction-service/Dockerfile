FROM openjdk:17-alpine
WORKDIR /transaction-service
COPY target/*.jar /transaction-service/app.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "/transaction-service/app.jar"]