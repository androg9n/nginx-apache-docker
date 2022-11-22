FROM httpd:2.4
COPY ./vhosts.attach /usr/local/apache2/conf/vhosts.attach
COPY ./organic-farm/ /usr/local/apache2/htdocs/organic-farm/
COPY ./design-portfolio-template/ /usr/local/apache2/htdocs/design-portfolio-template/

RUN cat /usr/local/apache2/conf/vhosts.attach >> /usr/local/apache2/conf/httpd.conf

