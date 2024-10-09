FROM openjdk:19-jdk-alpine
WORKDIR /app
COPY ./ConfigServer.jar /app/ConfigServer.jar
EXPOSE 80
ENV SPRING_PROFILES_ACTIVE=prod
ENTRYPOINT ["java", "-jar", "/app/ConfigServer.jar"]
