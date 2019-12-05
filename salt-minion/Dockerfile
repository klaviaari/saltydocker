FROM ubuntu:bionic

MAINTAINER Klaus Aho <klaus.aho@myy.haaga-helia.fi>

RUN apt-get update && apt-get install -y salt-minion curl

COPY setup.sh /opt/setup.sh

ENTRYPOINT ["sh","/opt/setup.sh"]
