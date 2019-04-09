FROM openjdk:8-jdk-slim
ADD app.jar app.jar
EXPOSE 6666
ENTRYPOINT ["java","-jar","app.jar","--server.port=6666"]
