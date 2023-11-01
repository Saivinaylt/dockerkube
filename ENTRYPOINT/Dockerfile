FROM almalinux:8
RUN yum install nginx -y
EXPOSE 80/tcp
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]