FROM openjdk:8-jdk-alpine
EXPOSE 8761
ADD target/eureka-service-0.0.1-SNAPSHOT.jar eureka-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["sh", "-c", "java -jar eureka-service-0.0.1-SNAPSHOT.jar"]