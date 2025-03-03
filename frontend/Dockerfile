FROM nginx
RUN rm -rf /usr/share/nginx/html/html.index
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY code /usr/share/nginx/html
