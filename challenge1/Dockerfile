# Use the official Nginx image from the Docker Hub
FROM nginx:latest

# Copy the public folder to the default Nginx public directory
COPY public /usr/share/nginx/html

# Expose port 80 to the host
EXPOSE 80

# Command to run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]

