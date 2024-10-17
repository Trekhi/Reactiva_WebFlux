FROM amazoncorretto:11
ARG JAR_FILE=target/resolve-enigma-api-2-1.0.0.jar
COPY ${JAR_FILE} app_step-two.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "app_step-two.jar"]
