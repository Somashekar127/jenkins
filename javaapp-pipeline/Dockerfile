FROM eclipse-temurin:21-jre

WORKDIR /app

COPY target/java-sample-21-1.0.0.jar app.jar

EXPOSE 5000

ENTRYPOINT ["java", "-jar", "app.jar"]
