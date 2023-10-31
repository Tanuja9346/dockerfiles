FROM almalinux:8
RUN yum install nginx -y
##expose is not adding any functonality, this is just for information
EXPOSE 80/tcp
CMD [ "nginx" ,"-g" , "daemon off;" ]