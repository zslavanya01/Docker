FROM    ubuntu
RUN     apt update
RUN     apt install nginx -y
CMD     ["nginx","-g","daemon off;"]
RUN     rm -rf /usr/share/nginx/html/*
ADD     index.html /usr/share/nginx/html/index.html