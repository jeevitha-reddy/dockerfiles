FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://github.com/jeevitha-reddy/learn-git.git /tmp/
ADD sample-1.tar /tmp/
CMD ["nginx","-g","daemon off;"]