# Using nginx web-server
FROM nginx
# Install cron
RUN apt-get update && \
    apt-get install -y nano
# Copy source code
COPY ../public /usr/share/nginx/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]