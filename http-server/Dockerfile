FROM httpd:2.4-alpine

COPY index.html /usr/local/apache2/htdocs/index.html
COPY httpd.conf /usr/local/apache2/conf/extra/httpd-reverse-proxy.conf

RUN echo "Include conf/extra/httpd-reverse-proxy.conf" >> /usr/local/apache2/conf/httpd.conf
