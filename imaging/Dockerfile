FROM            centos:7
RUN             yum install epel-release -y
RUN             yum install nginx -y
ENTRYPOINT      ["nginx", "-g", "daemon off;"]
EXPOSE          80
