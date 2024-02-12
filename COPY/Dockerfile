FROM almalinux:8
RUN yum install -y 
RUN rm -rf /usr/share/nginx/html/index.html
COPY inder.html /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]
