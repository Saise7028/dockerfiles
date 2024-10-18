FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/index/index.html
# this onbuild instruction runs only,when any user uses your image
ONBUILD COPY index.html /usr/share/nginx/index/index.html
CMD ["nginx", "-g", "daemon off;"]