FROM synocommunity/spksrc:latest
MAINTAINER SalmiRnD <https://salmi.com.se>

ENV NGINX_VERSION 1.12.1
ENV OPEN_SSL_VERSION 1_0_2l
ENV NGINX_RTMP_MODULE_VERSION 1.2.0

COPY build_nginx.sh /

# Volume pointing to spksrc sources
VOLUME /spksrc

WORKDIR /spksrc

ENTRYPOINT ["/build_nginx.sh"]
