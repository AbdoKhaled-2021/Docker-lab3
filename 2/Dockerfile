FROM httpd:2.4.57

COPY index.html /usr/local/apache2/htdocs/
COPY httpd.conf /usr/local/apache2/conf/httpd.conf

ENV CONTAINER="docker"

EXPOSE 9999
CMD ["sh", "-c", "echo $CONTAINER && httpd-foreground"]