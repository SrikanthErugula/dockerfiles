# FROM run:v1  
# it will comes from local repo if not in that.. we will get error like permission denied


FROM almalinux:9 
RUN dnf install nginx -y 
CMD ["nginx", "-g", "daemon off;"]