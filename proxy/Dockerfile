FROM nginx:alpine

# Remove default config and add our custom one
RUN rm /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/nginx.conf
