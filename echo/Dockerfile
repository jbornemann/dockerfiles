FROM centos:7

MAINTAINER Jeff Bornemann

RUN useradd -u 1000 echouser

RUN yum -y install nc

EXPOSE 8080

USER 1000

ENTRYPOINT ncat -v -l -p 8080 -c 'while true; do read i && echo $i; done' 
