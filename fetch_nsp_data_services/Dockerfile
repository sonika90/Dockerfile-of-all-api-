FROM localhost/openjdk:1.8
WORKDIR /opt
COPY target/nsp_process-0.0.1-SNAPSHOT.jar /opt/nsp_process-0.0.1-SNAPSHOT.jar
RUN ls
RUN pwd
EXPOSE 9083
ENTRYPOINT ["java", "-jar", "nsp_process-0.0.1-SNAPSHOT.jar"]



