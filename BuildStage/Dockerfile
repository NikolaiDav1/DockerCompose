FROM ubuntu:20.04
RUN apt-get update
RUN DEBIAN_FRONTEND=noninteractive TZ=Europe/Moscow apt-get -y install tzdata
RUN apt-get install default-jdk git maven -y
WORKDIR /tmp/
RUN git clone https://github.com/miladhub/calculator-servlet-example
WORKDIR /tmp/calculator-servlet-example/
RUN mvn package
