FROM openjdk:11
WORKDIR /app
COPY target/myapi-0.0.1-SNAPSHOT.jar /app
EXPOSE 8080

ENTRYPOINT [ "java", "-jar", "myapi-0.0.1-SNAPSHOT.jar" ]
