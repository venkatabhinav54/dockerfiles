FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY https://github.com/daws-81s/expense-infra-dev/blob/main/readme.MD /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]