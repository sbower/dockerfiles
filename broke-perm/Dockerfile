FROM ubuntu:12.04

RUN mkdir -p /infra/httpd/sessions
RUN chmod 700 /infra/httpd/sessions
RUN chown www-data:www-data /infra/httpd/sessions

USER www-data

CMD touch /infra/httpd/sessions/test