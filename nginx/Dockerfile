# Use the Nginx image
FROM nginx

# copy static files from staticFiles to /var/www
COPY ./staticFiles/ /var/www/html/

# Remove the default nginx.conf
RUN rm /etc/nginx/conf.d/default.conf

# Replace with our own nginx.conf
COPY nginx.conf /etc/nginx/conf.d/

