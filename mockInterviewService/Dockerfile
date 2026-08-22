FROM eclipse-temurin:25-jre

WORKDIR /app

COPY target/mockInterviewService-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8086

ENTRYPOINT ["java", "-jar", "app.jar"]
