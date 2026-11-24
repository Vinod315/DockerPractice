# dockerfiles/USER/Dockerfile
FROM almalinux:9
RUN useradd roboshop
RUN dnf install nginx -y



USER roboshop          
 # everything after this runs as roboshop, not root
CMD ["sleep", "100"]