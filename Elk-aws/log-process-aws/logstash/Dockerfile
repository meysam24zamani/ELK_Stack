FROM docker.elastic.co/logstash/logstash:7.0.0
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD pipeline/ /usr/share/logstash/pipeline/
COPY test_app.log  /usr/share/logstash/test_app.log
ADD config/ /usr/share/logstash/config/