FROM nginx

RUN rm /usr/share/nginx/html/50x.html

RUN rm /usr/share/nginx/html/index.html

COPY index.html /usr/share/nginx/html/

COPY 50x.html /usr/share/nginx/html/

COPY test.jpg /usr/share/nginx/html/

