FROM openjdk:11

WORKDIR /app

COPY target/spring-boot-with-metrics-*.jar app.jar

EXPOSE 8080

CMD ["java", "-jar", "app.jar"]