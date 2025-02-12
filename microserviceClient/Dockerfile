FROM openjdk:17
WORKDIR /app
COPY ./target/microserviceClient-1.0.0.jar cliente.jar
EXPOSE 8085
ENTRYPOINT ["java","-jar","client.jar"]