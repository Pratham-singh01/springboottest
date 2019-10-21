FROM openjdk:8
ADD . /opt/
COPY target/spring-boot-demo-0.0.1-SNAPSHOT.jar /opt/
EXPOSE 8080
ENTRYPOINT java -jar /opt/spring-boot-demo-0.0.1-SNAPSHOT.jar
