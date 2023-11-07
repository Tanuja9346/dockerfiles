FROM almalinux:8
RUN yum install nginx -y
RUN echo "hello, welcome to dockerfile. a way of creating own images" > /usr/share/nginx/html/hello.html
## one instruction one layer.
RUN yum install git -y \
    && yum install maven -y \
    &&  yum install gcc -y
RUN echo "HELLO WORLD"
CMD [ "nginx" ,"-g", "daemon off;" ]
