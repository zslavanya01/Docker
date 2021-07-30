FROM        ubuntu
RUN         apt update
RUN         apt install nginx -y
ENTRYPOINT  ["nginx","-g","daemon off;"]
LABEL       Owner="Zelarsoft" \
            Project="Todoapp"  \
            Maintainer="Devopsteam"
EXPOSE      80
