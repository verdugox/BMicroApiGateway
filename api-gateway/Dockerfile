FROM openjdk:11
VOLUME /tmp
EXPOSE 9040
ADD ./target/api-gateway-0.0.1-SNAPSHOT.jar ms-api-gateway.jar
ENTRYPOINT ["java", "-jar","/ms-api-gateway.jar"]

