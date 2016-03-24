FROM java:8-jre

MAINTAINER Jyong <yuki-nami@hotmail.com>
ENV REFRESHED_AT 2016-03-24

ENV TERRACOTTTA_HOME /usr/local/terracotta
COPY terracotta-3.7.10 $TERRACOTTTA_HOME
WORKDIR $TERRACOTTTA_HOME


CMD ["bin/start-tc-server.sh"]
