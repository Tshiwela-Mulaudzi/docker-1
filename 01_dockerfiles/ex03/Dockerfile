FROM ubuntu

EXPOSE 3000
EXPOSE 8022

RUN apt-get update -y && apt-get upgrade -y && apt-get install git -y && apt-get install wget -y && apt-get install -y build-essential && apt-get install gcc -y

RUN wget https://dl.gogs.io/0.11.66/gogs_0.11.66_linux_amd64.tar.gz && tar -xvf gogs_0.11.66_linux_amd64.tar.gz && cd gogs

ENV USER=root

WORKDIR /gogs

ENTRYPOINT ./gogs web

# How to build it?
# docker build -t ex03 .

# How to run it?
# docker run -i3
