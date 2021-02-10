FROM alpine:3.7

RUN apk add --no-cache git \
    && apk add --no-cache maven \
    && apk add --no-cache openjdk11 --repository=http://dl-cdn.alpinelinux.org/alpine/edge/community
#WORKDIR ./
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git 
WORKDIR /boxfuse-sample-java-war-hello
RUN mvn package
RUN ls -la
<<<<<<< HEAD
#CMD ["/bin/bash"]
=======
#CMD ["/bin/sh -c"]
>>>>>>> c42ba5083065a3997fea4a9727c629721b34308e
# cp /target/hello-1.0.war /hello-1.0.war

