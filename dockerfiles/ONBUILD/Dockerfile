# dockerfiles/ONBUILD/Dockerfile — the reusable base image (built as onbuild:v1)
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
ONBUILD COPY src/ /usr/share/nginx/html/   # runs in the CHILD build, not here
CMD ["nginx", "-g", "daemon off;"]
