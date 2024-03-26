FROM ubuntu:latest


Run apt-get update && apt-get install -y -q nginx

COPY index.html /usr/shar/nginx/html   

CMD ["nginx", "-g", "daemon off;"]
