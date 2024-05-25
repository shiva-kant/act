FROM openjdk:11-jre-slim
WORKDIR /app
ARG JAR_NAME
COPY target/${JAR_NAME} /app/app.jar
EXPOSE 8086
CMD ["java","-jar","/app/app.jar"]
