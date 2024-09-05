FROM alpine/java:22-jdk
COPY target/thrift-practice-service-0.0.1-SNAPSHOT.jar .
EXPOSE 9090
ENTRYPOINT ["java","-jar","thrift-practice-service-0.0.1-SNAPSHOT.jar"]
