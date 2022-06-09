FROM openjdk-11
WORKDIR /opt
COPY target/bankduplicationcheck-1.0.0-SNAPSHOT-runner.jar /opt/bankduplicationcheck-1.0.0-SNAPSHOT-runner.jar
RUN ls
RUN pwd
EXPOSE 7012

ENTRYPOINT ["java","-jar","bankduplicationcheck-1.0.0-SNAPSHOT-runner.jar"]

