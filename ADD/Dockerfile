FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/arunkumar261/roboshop-ansible-roles-duplicate-/main/main.yaml /tmp/
ADD sample-1.tar /tmp/