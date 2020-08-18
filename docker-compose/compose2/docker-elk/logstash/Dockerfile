##ARG ELK_VERSION

# https://github.com/elastic/logstash-docker
##FROM docker.elastic.co/logstash/logstash-oss:${ELK_VERSION}

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

FROM docker.elastic.co/logstash/logstash:7.0.0
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD pipeline/ /usr/share/logstash/pipeline/
ADD config/ /usr/share/logstash/config/
