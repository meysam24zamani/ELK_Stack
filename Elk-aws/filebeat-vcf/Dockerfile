FROM docker.elastic.co/beats/filebeat:7.0.1
COPY filebeat.yml /usr/share/filebeat/filebeat.yml
COPY dceoy-output.json  /usr/share/filebeat/dceoy-output.json
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml