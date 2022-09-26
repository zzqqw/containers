FROM elasticsearch:5.6

# https://www.elastic.co/guide/en/elasticsearch/reference/5.6/index.html

ADD plugins/ /usr/share/elasticsearch/plugins/

RUN  apt update && apt install -y gettext procps

EXPOSE 9200 9300
