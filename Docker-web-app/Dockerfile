# Use the official Nginx image from the Alpine Linux distribution
FROM nginx:alpine

# Set the working directory to the default web root directory for Nginx
WORKDIR /usr/share/nginx/html

# Copy all files from the current directory to the Nginx web root directory
COPY . /usr/share/nginx/html

# Expose port 80 to the host machine
EXPOSE 80

# Add metadata to the image
LABEL version="1.0" maintainer="Mickeydoe"
