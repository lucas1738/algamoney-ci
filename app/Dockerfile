FROM openjdk:8-jdk-slim
VOLUME /tmp
ADD app/target/algamoney-api-1.0.0-SNAPSHOT.jar app.jar
EXPOSE 8080
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java", "-jar", "/app.jar"]
