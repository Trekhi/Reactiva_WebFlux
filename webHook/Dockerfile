FROM amazoncorretto:21
ARG JAR_FILE=target/webHook-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app_webHook.jar
EXPOSE 8083
ENTRYPOINT ["java", "-jar", "app_webHook.jar"]
