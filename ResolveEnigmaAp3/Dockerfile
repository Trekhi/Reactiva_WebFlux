FROM amazoncorretto:11
ARG JAR_FILE=target/resolve-enigma-api-3-1.0.0.jar
COPY ${JAR_FILE} app_step-three.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_step-three.jar"]
