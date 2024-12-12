FROM almalinux:9
RUN dnf install nginx -y

RUN rm -rf /usr/share/nginx/html/index.html

ADD https://raw.githubusercontent.com/daws-81s/notes/refs/heads/main/session-01.txt

CMD ["nginx", "-g", "daemon off;"]