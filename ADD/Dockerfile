FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/DAWS-82S/notes/refs/heads/main/session-06.txt /usr/share/nginx/html/index.html
RUN chmod+x /usr/share/nginx/html/index.html 