FROM logstash:2.3

MAINTAINER WHITEPLUS System "sysadmin@wh-plus.com"

RUN logstash-plugin install logstash-output-amazon_es
RUN yes | /opt/logstash/bin/plugin update logstash-input-beats
