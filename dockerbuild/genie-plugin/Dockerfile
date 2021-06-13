FROM busybox:latest

ADD genie /opt/cni/bin/genie
ADD launch.sh /launch.sh
RUN chmod +x /launch.sh

ENV PATH=$PATH:/opt/cni/bin
VOLUME /opt/cni
WORKDIR /opt/cni/bin
