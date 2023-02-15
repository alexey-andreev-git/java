FROM openjdk:11-jdk
EXPOSE 8080
RUN mkdir -p /opt/app/
ADD simple-springboot-app/target/ /opt/app/
ENTRYPOINT ["java","-jar","/opt/app/simple-springboot-app-0.0.1-SNAPSHOT.jar"]
WORKDIR /opt/app