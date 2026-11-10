FROM almalinux:9
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html 
ADD https://githb.com/iam-rajeshmrk/Dockerfiles/raw/main/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]