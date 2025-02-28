FROM almalinux:9
RUN dnf install nginx -y
# There is no functionality fot expose, it is just for information
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]