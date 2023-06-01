FROM centos:8
RUN yum install nginx -y
RUN yum install epel-release -y
RUN rm-rf/usr/share/html/index.html
copy qi/usr/share/html/index.html
CMD ["nginx","-g","daemon off;"]