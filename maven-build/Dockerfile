FROM alpine:3.7

RUN apk add --no-cache git \
    && apk add --no-cache maven \
    && apk add --no-cache openjdk11 --repository=http://dl-cdn.alpinelinux.org/alpine/edge/community
#WORKDIR ./
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git 
WORKDIR /boxfuse-sample-java-war-hello
RUN mvn package
RUN ls -la
CMD ["/bin/sh -c"]
# cp /target/hello-1.0.war /hello-1.0.war

