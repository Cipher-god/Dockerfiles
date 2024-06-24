# for creating the webserver
FROM nginx:alpine

# copying website files to nginx html dir
COPY . /usr/share/nginx/html

# exposing the port 80 to access the website
EXPOSE 80

# command to start nginx when this container is running
CMD ["nginx", "-g", "daemon off;"]