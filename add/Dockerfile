FROM    ubuntu
RUN     apt update
RUN     apt install nginx -y
CMD     ["nginx","-g","daemon off;"]
RUN     rm -rf /var/www/html/*
#ADD     --chown=www-data:www-data index.html /var/www/html/index.html
COPY    html /var/www/html