FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/htmlindes.html 
ONBUILD ADD index.html /usr/share/nginx/htmlindes.html 
CMD [ "nginx", "-g", "daemon off;" ]