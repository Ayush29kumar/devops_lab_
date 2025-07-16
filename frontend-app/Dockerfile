# Use the official NGINX image as the base image
FROM nginx:alpine

# Remove the default nginx index page
RUN rm -rf /usr/share/nginx/html/*

# Copy your custom index.html to the nginx web root
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
