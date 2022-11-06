FROM nginx:alpine

# Remove existing default.conf file
RUN rm /etc/nginx/conf.d/default.conf

# Copy static page and default.conf
COPY ./index.html /usr/share/nginx/html
COPY ./default.conf etc/nginx/conf.d/default.conf