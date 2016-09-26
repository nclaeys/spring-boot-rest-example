FROM java:8

RUN mkdir -p opt

ADD ./rest-example-boot.jar /opt

WORKDIR /opt

RUN chmod +x rest-example-boot.jar

CMD ["java","-Dspring.profiles.active=mysql","-jar","rest-example-boot.jar"]

EXPOSE 8090 8091