FROM alpine:3.10
RUN apk add --no-cache openjdk8-jre
COPY helloworld.jar /root/
CMD ["java", "-jar", "/root/helloworld.jar"]