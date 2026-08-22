FROM eclipse-temurin:25-jre

WORKDIR /app

COPY target/answerService-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8084

ENTRYPOINT ["java", "-jar", "app.jar"]