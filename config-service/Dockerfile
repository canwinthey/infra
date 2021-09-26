FROM openjdk:8-jdk-alpine
EXPOSE 8888
ADD target/config-service-0.0.1-SNAPSHOT.jar config-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["sh", "-c", "java -jar config-service-0.0.1-SNAPSHOT.jar"]