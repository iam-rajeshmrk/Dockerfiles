FROM almalinux:9
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# this executes if any user uses your image as their base OS
ONBUILD copy index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g", "daemon off;"]
