FROM centos:6.4
MAINTAINER Cameron King <http://cameronking.me>

RUN yum -y install java-1.6.0-openjdk
RUN useradd -mUs /bin/false -d /minecraft minecraft

VOLUME ["/minecraft"]

EXPOSE 25565
ADD start.sh /start.sh

CMD ["/start.sh"]

