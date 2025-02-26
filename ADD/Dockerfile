FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY https://github.com/charansuravarapu/Dockerfiles/tree/main /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
