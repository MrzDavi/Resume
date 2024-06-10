
FROM openjdk:11-jre-slim


COPY target/sua-aplicacao.jar /app/sua-aplicacao.jar


WORKDIR /app


EXPOSE 8080

# Execute
CMD ["java", "-jar", "sua-aplicacao.jar"]
