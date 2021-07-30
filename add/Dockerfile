FROM    ubuntu
RUN     apt update
RUN     apt install nginx -y
CMD     ["nginx","-g","daemon off;"]
ADD     index.html /usr/share/nginx/html/index.html