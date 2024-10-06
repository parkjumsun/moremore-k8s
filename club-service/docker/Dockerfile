FROM openjdk:19-jdk-alpine
WORKDIR /app
COPY ./ClubService.jar /app/ClubService.jar
EXPOSE 80
ENV SPRING_PROFILES_ACTIVE=prod
ENTRYPOINT ["java", "-jar", "/app/ClubService.jar"]
