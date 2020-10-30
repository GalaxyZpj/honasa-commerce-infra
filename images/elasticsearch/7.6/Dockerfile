FROM elasticsearch:7.6.2
LABEL Maintainer="Kevin Solomon <ikevinsolomon@gmail.com>" \
      Description="Lightweight container with elasticsearch"

RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install analysis-icu
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install analysis-phonetic
