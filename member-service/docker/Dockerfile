FROM openjdk:19-jdk-alpine
WORKDIR /app
COPY ./MemberService.jar /app/MemberService.jar
EXPOSE 80
ENV SPRING_PROFILES_ACTIVE=prod
ENTRYPOINT ["java", "-jar", "/app/MemberService.jar"]
