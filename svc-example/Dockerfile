FROM eipwork/jdk:1.0.0

ARG JAR_FILE_NAME=svc-example-0.0.1-SNAPSHOT.jar
ARG PORT=9301
ARG MANAGEMENT_PORT=9401

EXPOSE $PORT
EXPOSE $MANAGEMENT_PORT

WORKDIR /eip
COPY ./target/$JAR_FILE_NAME $JAR_FILE_NAME

ENV JAR_FILE_NAME=$JAR_FILE_NAME
ENV PINPOINT_APP_NAME=svc-example

