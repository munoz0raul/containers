FROM nginx

RUN rm /usr/share/nginx/html/50x.html

COPY webserver/index.html /usr/share/nginx/html/

COPY webserver/assets/bootstrap/bootstrap4-alpha3.min.js /usr/share/nginx/html/assets/bootstrap/bootstrap4-alpha3.min.js
COPY webserver/assets/bootstrap/bootstrap4-alpha3.min.css /usr/share/nginx/html/assets/bootstrap/bootstrap4-alpha3.min.css
COPY webserver/assets/fonts/font-roboto.css /usr/share/nginx/html/assets/fonts/font-roboto.css
COPY webserver/assets/tether/tether.min.js /usr/share/nginx/html/assets/tether/tether.min.js
COPY webserver/assets/web-analytics/style.css /usr/share/nginx/html/assets/web-analytics/style.css
COPY webserver/assets/web-analytics/real-time.js /usr/share/nginx/html/assets/web-analytics/real-time.js
COPY webserver/assets/jquery/jquery-3.1.0.min.js /usr/share/nginx/html/assets/jquery/jquery-3.1.0.min.js
COPY webserver/assets/font-awesome/css/font-awesome.min.css /usr/share/nginx/html/assets/font-awesome/css/font-awesome.min.css
