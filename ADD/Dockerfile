FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/diagrams/refs/heads/main/Untitled%20Diagram.drawio /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
