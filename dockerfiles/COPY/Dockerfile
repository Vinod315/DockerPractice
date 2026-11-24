# dockerfiles/COPY/Dockerfile
FROM nginx
RUN rm -rf /usr/share/nginx/html/*    # clear the default nginx page
COPY qi/ /usr/share/nginx/html/       # copy our site in