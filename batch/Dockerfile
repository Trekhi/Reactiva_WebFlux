FROM amazoncorretto:21
ARG JAR_FILE=target/batch-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app_batch.jar
EXPOSE 8078
ENTRYPOINT ["java", "-jar", "app_batch.jar"]

