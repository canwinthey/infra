FROM openjdk:8-jdk-alpine
EXPOSE 8061
ADD target/gateway-service-0.0.1-SNAPSHOT.jar gateway-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["sh", "-c", "java -jar gateway-service-0.0.1-SNAPSHOT.jar"]