FROM openjdk:19-jdk-alpine
WORKDIR /app
COPY ./NotificationService.jar /app/NotificationService.jar
EXPOSE 80
ENV SPRING_PROFILES_ACTIVE=prod
ENTRYPOINT ["java", "-jar", "/app/NotificationService.jar"]
