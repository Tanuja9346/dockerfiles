FROM almalinux:8
#almalinux same as centos
RUN yum install nginx -y
RUN rm -rf  /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
# this will not excuted at the time of build his image.then when it will excuted is index.html is mandatroty in workspace.
#daemon off command makes our container running and attached to screen
CMD [ "nginx" ,"-g", "daemon off;" ]
