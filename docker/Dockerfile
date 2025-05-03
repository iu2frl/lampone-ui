# Using nginx web-server
FROM nginx
# Copy source code
COPY ../public /usr/share/nginx/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]