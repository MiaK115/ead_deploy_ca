FROM nginx:1.27-alpine

# Fix CVEs by upgrading base packages at build time
RUN apk --no-cache upgrade

COPY nginx.conf /etc/nginx/nginx.conf