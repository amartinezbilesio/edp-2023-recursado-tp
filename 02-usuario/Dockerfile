FROM ubuntu:latest

RUN apt-get update
RUN apt-get install -y curl file

ADD ["opt/","/opt/"]

WORKDIR /opt/src

ENTRYPOINT ["/opt/src/menu.sh"]
