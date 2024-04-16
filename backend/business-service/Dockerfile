FROM openjdk:11.0-jdk-slim
WORKDIR /business-service
COPY target/*.jar /business-service/app.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "/business-service/app.jar"]