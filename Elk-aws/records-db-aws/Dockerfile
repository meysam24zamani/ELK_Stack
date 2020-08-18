FROM docker.elastic.co/logstash/logstash:7.0.0
USER root
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD pipeline/ /usr/share/logstash/pipeline/
COPY postgresql-9.4-1201-jdbc41.jar  /usr/share/logstash/postgresql-9.4-1201-jdbc41.jar
COPY rds-combined-ca-bundle.pem  /usr/share/logstash/rds-combined-ca-bundle.pem
ADD config/ /usr/share/logstash/config/