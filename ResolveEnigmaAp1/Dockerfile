FROM amazoncorretto:11
ARG JAR_FILE=target/resolve-enigma-api-1-1.0.0.jar
COPY ${JAR_FILE} app_step-one.jar
EXPOSE 8079
ENTRYPOINT ["java", "-jar", "app_step-one.jar"]
