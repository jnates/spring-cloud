FROM openjdk:17-alpine
VOLUME /tmp
EXPOSE 9090
COPY application.properties /application.properties
COPY api-gateway-0.0.1.jar /api-gateway-0.0.1.jar
ENTRYPOINT [ "java","-jar","api-gateway-0.0.1.jar" ]
