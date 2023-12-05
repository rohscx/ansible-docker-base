# Latest Ubuntu LTS
FROM ubuntu:20.04
MAINTAINER Erou Foster
RUN apt-get update && \
    apt-get install --no-install-recommends -y software-properties-common && \
    apt-add-repository ppa:ansible/ansible && \
    apt-get update && \
    apt install git -y && \
    apt install vim -y && \
    apt-get install -y ansible

RUN echo '[local]\nlocalhost\n' > /etc/ansible/hosts

