FROM nginx:alpine

COPY nginx.conf /etc/nginx/nginx.conf
COPY demosite.dev /etc/nginx/sites-available/demosite.dev
COPY test.demosite.dev /etc/nginx/sites-available/test.demosite.dev

CMD service nginx start