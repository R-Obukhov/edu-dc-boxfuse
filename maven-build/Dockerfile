FROM maven:3.6.1-jdk-8-alpine

COPY ./boxfuse-sample-java-war-hello/* ./
RUN mvn package && cp target/hello-1.0.war /hello-1.0.war

