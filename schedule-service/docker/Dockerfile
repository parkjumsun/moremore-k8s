FROM openjdk:19-jdk-alpine
WORKDIR /app
COPY ./ScheduleService.jar /app/ScheduleService.jar
EXPOSE 80
ENV SPRING_PROFILES_ACTIVE=prod
ENTRYPOINT ["java", "-jar", "/app/ScheduleService.jar"]
