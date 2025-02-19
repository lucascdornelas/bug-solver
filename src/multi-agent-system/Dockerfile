FROM ubuntu:latest

RUN apt-get update

RUN apt install git -y

RUN apt install python3 -y

RUN apt install python3-pip -y

RUN mkdir -p /agent_workspace

WORKDIR /agent_workspace

CMD ["/bin/bash"]