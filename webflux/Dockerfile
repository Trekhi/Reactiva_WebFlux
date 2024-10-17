FROM amazoncorretto:21
ARG JAR_FILE=target/webflux-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app_webflux.jar
EXPOSE 9000
ENTRYPOINT ["java", "-jar", "app_webflux.jar"]
