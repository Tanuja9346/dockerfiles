FROM almalinux:8
#almalinux same as centos
RUN yum install nginx -y
RUN rm -rf  /usr/share/nginx/html/hello.html
RUN echo "hello, welcome to dockerfile. a way of creating own images" > /usr/share/nginx/html/hello.html
#daemon off command makes our container running and attached to screen
ENTRYPOINT [ "nginx" ,"-g", "daemon off;" ]
