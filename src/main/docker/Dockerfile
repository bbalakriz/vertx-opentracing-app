FROM maven:3.6.3-openjdk-11 as builder
WORKDIR /project
COPY . /project/
RUN mvn package -DskipTests -B
