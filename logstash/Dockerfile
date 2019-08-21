# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:7.3.0

COPY pipeline/logstash.conf /usr/share/logstash/pipeline/logstash.conf

RUN chmod 0777 /usr/share/logstash/data


# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
