FROM openjdk:19-jdk-alpine
WORKDIR /app
COPY ./PostingService.jar /app/PostingService.jar
EXPOSE 80
ENV SPRING_PROFILES_ACTIVE=prod
ENTRYPOINT ["java", "-jar", "/app/PostingService.jar"]
