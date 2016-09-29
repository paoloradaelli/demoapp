FROM nginx:alpine
ADD *.png /usr/share/nginx/html/
ADD index.html /usr/share/nginx/html/index.html
RUN sed -i '/http {/a\               expires off;' /etc/nginx/nginx.conf  
