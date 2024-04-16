FROM openjdk:11.0-jdk-slim
WORKDIR /transaction-service
COPY target/*.jar /transaction-service/app.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "/transaction-service/app.jar"]