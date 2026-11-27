FROM eclipse-temurin:24-jre
WORKDIR /app
COPY build/libs/*.jar app.jar
EXPOSE 7002
ENTRYPOINT ["java", "-jar", "app.jar"]
