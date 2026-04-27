FROM almalinux:9
RUN yum install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
#this ONBUILD instruction runs when someone uses this image
ONBUILD COPY index.html /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]