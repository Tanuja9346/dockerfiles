FROM almalinux:8
#almalinux same as centos
RUN yum install nginx -y
RUN echo "hello, welcome to dockerfile. a way of creating own images" > /usr/share/nginx/hello.html
#daemon off command makes our container running and attached to screen
CMD [ "nginx" "-g" "daemon off;" ]
