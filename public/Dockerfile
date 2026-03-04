FROM nginx:latest

# Copy custom nginx config
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Copy HTML files
COPY . /usr/share/nginx/html/

EXPOSE 80