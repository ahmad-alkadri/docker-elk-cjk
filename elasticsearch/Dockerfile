ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION:-8.15.3}

# Install ICU Analysis Plugin for CJK support
RUN elasticsearch-plugin install analysis-icu