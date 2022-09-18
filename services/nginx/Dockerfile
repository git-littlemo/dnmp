ARG NGINX_VERSION

FROM ${NGINX_VERSION}

ARG TZ

RUN cp /usr/share/zoneinfo/${TZ} /etc/localtime && \
    mkdir -p -m 755 /var/log/nginx && \
    chown -R nginx:nginx /var/log/nginx