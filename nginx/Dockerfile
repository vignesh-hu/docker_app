FROM nginx:stable

RUN rm -f /etc/nginx/conf.d/*

ADD /nginx/nginx.conf /etc/nginx/conf.d/docker.conf

CMD /usr/sbin/nginx -g 'daemon off;' -c /etc/nginx/nginx.conf