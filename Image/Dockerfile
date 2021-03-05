FROM jenkins

COPY ./contrib/jenkins /usr/local/bin
ADD plugins.txt /opt

RUN /usr/local/bin/install-plugins.sh /opt/plugins.txt

