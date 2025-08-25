FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/concepts/refs/heads/main/memory-troubleshoot.MD /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]
