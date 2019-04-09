FROM openjdk:8-jdk-slim
ADD app.jar app.jar
EXPOSE 9002
ENTRYPOINT ["java","-jar","app.jar","--server.port=9002"]
