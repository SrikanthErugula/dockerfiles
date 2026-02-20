FROM nginx
# here removed defalut content 
RUN rm -rf /usr/share/nginx/html/index.html

# copied our code in that path
COPY index.html /usr/share/nginx/html/index.html
#COPY qi/ /usr/share/nginx/html/