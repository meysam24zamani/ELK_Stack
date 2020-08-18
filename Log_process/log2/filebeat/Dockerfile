FROM docker.elastic.co/beats/filebeat:7.0.1
COPY filebeat.yml /usr/share/filebeat/filebeat.yml
COPY log.test  /usr/share/filebeat/log.test
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml