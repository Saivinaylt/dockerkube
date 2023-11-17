FROM almalinux:8
RUN yum update -y
RUN yum install stress-ng -y
RUN echo "his this strees-ng occuping the system cpu and memory space eg stress-ng --cpu 1" > /tmp/sai.txt
CMD ["stress-ng", "--help"]