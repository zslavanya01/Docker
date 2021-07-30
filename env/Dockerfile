FROM    ubuntu
RUN     apt update
RUN     apt install nginx -y
CMD     ["nginx","-g","daemon off;"]
LABEL   Owner="Zelarsoft" \
        Project="Todoapp"  \
        Maintainer="Devopsteam"
EXPOSE  80
ENV     URL=google.com
ENV     PROJECT=DEMO