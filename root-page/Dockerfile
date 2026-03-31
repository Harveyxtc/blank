# Use tiny Nginx image
FROM nginx:alpine

# Copy everything in this folder (index.html, etc) to Nginx web root
COPY . /usr/share/nginx/html

# Expose the standard HTTP port
EXPOSE 80

# Start Nginx in foreground
CMD ["nginx", "-g", "daemon off;"]
