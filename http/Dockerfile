FROM httpd:latest
COPY ./httpd.conf /usr/local/apache2/conf/httpd-custom.conf
COPY ./public-html/ /usr/local/apache2/htdocs/
RUN echo "Include ./conf/httpd-custom.conf" >> /usr/local/apache2/conf/httpd.conf