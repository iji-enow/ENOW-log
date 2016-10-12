FROM elasticsearch:latest

ADD config/elasticsearch.yml /elasticsearch/config/elasticsearch.yml
RUN /usr/share/elasticsearch/bin/plugin install --batch royrusso/elasticsearch-HQ
RUN /usr/share/elasticsearch/bin/plugin install --batch https://github.com/NLPchina/elasticsearch-sql/releases/download/2.4.1.0/elasticsearch-sql-2.4.1.0.zip
