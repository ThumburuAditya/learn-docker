FROM ubuntu:18.04
LABEL maintainer="adityathumburu1999@gmail.com"
VOLUME /var/lib/docker/volumes
RUN apt-get update && apt-get -y install apache2
EXPOSE 80
ENTRYPOINT ["/usr/sbin/apachectl"]
CMD ["-D", "FOREGROUND"]