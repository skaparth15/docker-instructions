FROM almalinux:9
RUN dnf install nginx -y
RUN rm /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
CMD  ["nginx", "-g", "daemon off;"]
LABEL course="devops" \
      name="charan"
EXPOSE 80/tcp
ENV concept=docker-instructions


