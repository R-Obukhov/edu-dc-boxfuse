FROM alpine:3.7

RUN apk add --no-cache git \
    && apk add --no-cache maven \
    && apk add --no-cache openjdk11 --repository=http://dl-cdn.alpinelinux.org/alpine/edge/community

RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git 
WORKDIR /boxfuse-sample-java-war-hello
RUN mvn package

