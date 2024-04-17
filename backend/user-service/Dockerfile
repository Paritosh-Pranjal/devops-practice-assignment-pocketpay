FROM openjdk:17-alpine
WORKDIR /user-service
COPY target/*.jar /user-service/app.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "/user-service/app.jar"]