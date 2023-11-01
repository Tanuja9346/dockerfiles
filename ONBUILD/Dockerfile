FROM almalinux:8
#almalinux same as centos
RUN yum install nginx -y
RUN rm -rf  /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
#daemon off command makes our container running and attached to screen
CMD [ "nginx" ,"-g", "daemon off;" ]
