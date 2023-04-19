FROM openjdk:11
RUN mkdir/app
WORKDIR /app
COPY target/myapi-0.0.1-SNAPSHOT.jar
EXPOSE 8110

ENTRYPOINT [ "java", "-jar", "myapi-0.0.1-SNAPSHOT.jar" ]