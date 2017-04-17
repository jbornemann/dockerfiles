FROM centos:7

MAINTAINER Jeff Bornemann

RUN useradd -u 7000 -g root myuser

USER 2100

RUN touch /home/myuser/file

ENTRYPOINT while true; do id && sleep 10; done
