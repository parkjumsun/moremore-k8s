FROM openjdk:17-ea-11-jdk-slim
WORKDIR /app
COPY ./Gateway.jar /app/Gateway.jar
EXPOSE 31080
ENTRYPOINT ["java", "-jar", "/app/Gateway.jar"]
