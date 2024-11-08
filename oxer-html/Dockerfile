# Use the official NGINX image as the base image
FROM nginx:alpine

# Set the working directory in the container
WORKDIR /usr/share/nginx/html

# Copy the static website files from your project to the container
COPY oxer-html /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX (this command is defined in the NGINX image, so no need to add a custom command)

