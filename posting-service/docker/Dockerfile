FROM openjdk:17-ea-11-jdk-slim
WORKDIR /app
COPY ./PostingService.jar /app/PostingService.jar
EXPOSE 80
ENV SPRING_PROFILES_ACTIVE=prod
ENTRYPOINT ["java", "-jar", "/app/PostingService.jar"]
