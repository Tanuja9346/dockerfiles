FROM almalinux:8
#removing default html
RUN rm -rf /usr/share/nginx/html/index.html
#files should be available in current directory where dockerfiles exist.
COPY index.html /usr/share/nginx/html/index.html
