FROM adoptopenjdk/openjdk11:alpine

COPY build/libs/helloworld-server-all.jar /java/
RUN chmod +x /java/*
WORKDIR /java
ENTRYPOINT [ "java", "-jar", "/java/helloworld-server-all.jar" ]