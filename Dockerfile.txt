# Use official Nginx image from Docker Hub
FROM nginx:latest

# Copy the contents of your current directory (website files) to the Nginx HTML directory
COPY . /usr/share/nginx/html
