FROM elasticsearch:1.7.1
MAINTAINER P. Barrett Little <barrett@barrettlittle.com> (@pblittle)

ENV ES_HOME /usr/share/elasticsearch

ENV PATH ${ES_HOME}/bin:$PATH

ENV CLOUD_AWS_VERSION 2.7.1

RUN plugin --install elasticsearch/elasticsearch-cloud-aws/${CLOUD_AWS_VERSION}
