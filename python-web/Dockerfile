FROM python:3

MAINTAINER Jeff Bornemann

RUN useradd -u 1000 pyuser

EXPOSE 8080

USER 1000

ENTRYPOINT python -m http.server 8080 
