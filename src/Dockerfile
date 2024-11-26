FROM openjdk:17-jdk-slim

COPY HelloWorld.java /src/HelloWorld.java

WORKDIR /src

RUN javac HelloWorld.java

CMD ["java", "HelloWorld"]