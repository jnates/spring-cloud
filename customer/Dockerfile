FROM openjdk:17-alpine
VOLUME /tmp
EXPOSE 9092
COPY application.properties /application.properties
COPY bank-customer-0.0.1.jar /bank-customer-0.0.1.jar
ENTRYPOINT [ "java","-jar","bank-customer-0.0.1.jar" ]
