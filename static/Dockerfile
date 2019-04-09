FROM openjdk:8-jdk-slim
ADD app.jar app.jar
EXPOSE 5555
ENTRYPOINT ["java","-jar","app.jar","--server.port=5555"]
