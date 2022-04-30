FROM openjdk:17-alpine
VOLUME /tmp
EXPOSE 9091
COPY application.properties /application.properties
COPY bank-balance-0.0.1.jar /bank-balance-0.0.1.jar
ENTRYPOINT [ "java","-jar","bank-balance-0.0.1.jar" ]
