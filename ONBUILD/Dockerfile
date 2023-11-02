FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/htmlindes.html 
ONBUILD ADD index.html /usr/share/nginx/htmlindes.html 
RUN echo "hi good morning" > /tmp/hi.txt
CMD [ "nginx", "-g", "daemon off;" ]