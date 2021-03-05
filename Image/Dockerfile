FROM jenkins/jenkins

COPY ./contrib/jenkins /usr/local/bin
ADD plugins.txt /opt

USER root
RUN /usr/local/bin/install-plugins.sh /opt/plugins.txt

