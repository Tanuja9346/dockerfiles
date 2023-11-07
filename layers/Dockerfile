FROM almalinux:8
RUN yum install nginx -y
RUN echo "hello, welcome to dockerfile. a way of creating own images" > /usr/share/nginx/html/hello.html
CMD [ "nginx" ,"-g", "daemon off;" ]
