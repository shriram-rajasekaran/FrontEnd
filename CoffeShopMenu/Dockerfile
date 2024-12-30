# Use the official Nginx image as the base image
FROM nginx:alpine

# Copy your static files to the Nginx default web directory
COPY index.html /usr/share/nginx/html/
COPY styles.css /usr/share/nginx/html/

# Expose the default Nginx port
EXPOSE 80

