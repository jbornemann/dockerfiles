FROM centos:7

MAINTAINER Jeff Bornemann

RUN yum install -y nc
    
RUN useradd -u 7000 -g root myuser

USER 7000

RUN touch /home/myuser/file

EXPOSE 8080

ENTRYPOINT nc -l 8080 --keep-open --exec id
