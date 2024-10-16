#I'm the author of this image
FROM almalinux:9
RUN dnf install nginx -y
CMD [ "nginx", "-g", "daemon off;" ]
#to start nginx
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html 