FROM openjdk:8-alpine
RUN apk --update add wget tar bash
RUN wget http://apache.mirror.anlx.net/spark/spark-2.4.0/spark-2.4.0-bin-hadoop2.7.tgz

RUN tar -xzf spark-2.4.0-bin-hadoop2.7.tgz && \
    mv spark-2.4.0-bin-hadoop2.7 /spark && \
    rm spark-2.4.0-bin-hadoop2.7.tgz

