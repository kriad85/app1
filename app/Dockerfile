FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
ADD target/app1.jar app1.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app1.jar"]
