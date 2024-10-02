FROM openjdk:17-ea-11-jdk-slim
WORKDIR /app
COPY ./UserService.jar /app/UserService.jar
EXPOSE 80
ENV SPRING_PROFILES_ACTIVE=prod
ENTRYPOINT ["java", "-jar", "/app/UserService.jar"]
