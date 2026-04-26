FROM almalinux:9
CMD ["nginx","-g","daemon off;"]
RUN rm -f /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
#COPY qi/ /usr/share/nginx/html