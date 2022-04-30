FROM openjdk:17-alpine
VOLUME /tmp
EXPOSE 1111
COPY application.properties /application.properties
COPY eureka-server-0.0.1.jar /eureka-server-0.0.1.jar
ENTRYPOINT [ "java","-jar","eureka-server-0.0.1.jar" ]
