# dockerfiles/WORKDIR/Dockerfile
FROM almalinux:9
RUN cd /tmp                    
   # has NO lasting effect — the cd is gone after this layer
RUN mkdir /app
WORKDIR /app                   
   # this DOES persist
RUN echo "Present directory: ${PWD}"   # → /app
CMD ["sleep", "100"]