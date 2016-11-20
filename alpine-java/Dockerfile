FROM alpine

RUN apk add --update openjdk8-jre

RUN mkdir /work
ADD java-expr/target/*.jar /work

CMD ["/bin/sh"]
