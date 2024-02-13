FROM almalinux:latest
RUN yum install nginx -yum
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
CMD [ "nginx","-g","daemon off;" ]