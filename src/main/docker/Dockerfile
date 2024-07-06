FROM amd64/openjdk:21

RUN mkdir /usr/src/app

COPY target/quarkus-app/ /usr/src/app

WORKDIR /usr/src/app

CMD ["java", "-jar", "quarkus-run.jar"]