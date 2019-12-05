FROM ubuntu:18.04

MAINTAINER Klaus Aho <klaus.aho@myy.haaga-helia.fi>

RUN apt-get update && apt-get install -y salt-master

COPY setup.sh /opt/setup.sh

ENTRYPOINT ["sh","/opt/setup.sh"]
