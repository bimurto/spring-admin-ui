FROM openjdk:8-jdk-alpine
ARG JAR_FILE=build/libs/admin-server-1.0.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]