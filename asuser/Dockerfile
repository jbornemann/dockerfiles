FROM centos:7

MAINTAINER Jeff Bornemann

RUN useradd -u 7000 -g root myuser

USER 7000

ENTRYPOINT id; while true; do sleep 10; done
