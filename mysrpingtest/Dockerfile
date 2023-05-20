FROM eclipse-temurin:17-jdk-jammy
EXPOSE 8080
ARG JAR_FILE_PATH=build/libs/*SNAPSHOT.jar
COPY ${JAR_FILE_PATH} app.jar
ENTRYPOINT [ "java", "-jar", "app.jar" ]