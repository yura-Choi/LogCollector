FROM docker.elastic.co/logstash/logstash:8.7.1

COPY ./config/logstash.yml /usr/share/logstash/config/logstash.yml
COPY ./pipeline/pip_test.config /usr/share/logstash/pipeline/pip_test.config
USER root

RUN chown -R root /usr/share/logstash
