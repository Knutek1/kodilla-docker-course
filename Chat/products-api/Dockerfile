FROM openjdk:latest

ARG JAR_FILE

COPY ${JAR_FILE} app.jar

EXPOSE 8080

CMD ["java", "-jar", "app.jar"]