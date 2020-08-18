FROM docker.elastic.co/beats/filebeat:7.0.1
COPY filebeat.yml /usr/share/filebeat/filebeat.yml
COPY test_app.log  /usr/share/filebeat/test_app.log
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml